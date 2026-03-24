# Analyse : erreur "Unable to populate IG flag information"

## Symptôme

Lors du build, 5 occurrences de :

```
ERROR: Unable to populate IG flag information: Unable to find 2-char ISO country code: FR
```

Et pour toutes les nations (3 lettres) :

```
No display value for 3-character country code AFG
No display value for 3-character country code ALB
...
```

---

## Analyse du code source du publisher (v2.2.2)

La méthode impliquée est `PublisherGenerator.setupCountries()` → `translateCountryCode()`.

### Chaîne causale complète

#### Étape 1 — Expansion du ValueSet ISO 3166 (3 lettres)

Le publisher tente d'expanser localement :

```json
{
  "resourceType": "ValueSet",
  "compose": {
    "include": [{
      "system": "urn:iso:std:iso:3166",
      "filter": [{ "property": "code", "op": "regex", "value": "^[A-Z]{3}$" }]
    }]
  }
}
```

L'expansion **réussit** (`isOk() = true`) mais les items n'ont **pas de `display`**, car le CodeSystem ISO 3166 dans le package `hl7.terminology.r4` ne contient pas les libellés — ils ne sont disponibles qu'en interrogeant le serveur de terminologie en ligne (tx.fhir.org).

→ **`countryCodeForName` (display → code 3 lettres) reste vide.**

#### Étape 2 — Expansion du ValueSet ISO 3166 (2 lettres)

Le publisher tente d'expanser :

```json
{
  "compose": {
    "include": [{
      "system": "urn:iso:std:iso:3166",
      "filter": [{ "property": "code", "op": "regex", "value": "^[A-Z]{2}$" }]
    }]
  }
}
```

Pour chaque code 2 lettres (ex: code=`FR`, display=`France`) :

```java
var12 = countryCodeForName.get("France"); // → null, car countryCodeForName est vide
```

Étant donné que `var12 == null`, les puts suivants sont sautés :

```java
countryCodeFor2Letter.put("FR", var12);  // jamais exécuté
shortCountryCode.put(var12, "FR");       // jamais exécuté
```

→ **`countryCodeFor2Letter` et `shortCountryCode` restent vides.**

#### Étape 3 — Appel de `translateCountryCode("FR")`

```java
private String translateCountryCode(String code) {
    setupCountries(); // maps vides
    if (code.length() == 2) {
        String result = countryCodeFor2Letter.get(code); // → null
        if (result == null)
            throw new Exception("Unable to find 2-char ISO country code: " + code);
    }
    ...
}
```

→ **Exception levée**, capturée par le handler qui loggue `ERROR: Unable to populate IG flag information: Unable to find 2-char ISO country code: FR`.

#### Étape 4 — URL du flag non construite

Si `translateCountryCode` avait réussi, le publisher aurait tenté de télécharger le flag depuis :

```
http://flags.ox3.in/svg/{shortCode}/{code}.svg
```

---

## Cause racine

**Le package `hl7.terminology.r4` ne contient pas les libellés (`display`) des codes ISO 3166.**
Sans connexion au tx server (tx.fhir.org), l'expansion locale retourne des codes sans display.
La logique de `setupCountries()` repose entièrement sur ces display pour construire le mapping 3 lettres → 2 lettres.

---

## Impact

L'erreur est **non bloquante** : le build se termine normalement, les flags sont simplement absents des pages générées.

---

## Solutions possibles

### Option 1 — Accepter et supprimer le message (court terme)

Ajouter dans `input/ignoreWarnings.txt` :

```
Unable to populate IG flag information
```

### Option 2 — Passer par le tx server en ligne (recommandé)

Configurer le build pour utiliser le tx server externe (tx.fhir.org), qui retourne les display values des codes ISO 3166. Cela permet à `countryCodeForName` d'être peuplé correctement.

### Option 3 — Reporter un bug au publisher

La logique de `setupCountries()` devrait gérer gracieusement l'absence de display dans les codes ISO 3166 (cas courant en build offline). Le code actuel ne prévoit pas ce fallback.

→ Reporter sur : https://github.com/HL7/fhir-ig-publisher/issues

---

## Références

- `PublisherGenerator.java` → méthodes `setupCountries()`, `translateCountryCode()`, `displayForCountryCode()`
- `PublisherFields.java` → maps : `countryCodeFor2Letter`, `shortCountryCode`, `countryCodeForName`, `countryNameForCode`
- URL flags : `http://flags.ox3.in/svg/{shortCode}/{code}.svg`
