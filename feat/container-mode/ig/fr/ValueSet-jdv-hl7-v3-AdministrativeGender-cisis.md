# AdministrativeGender - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Résumé des artefacts**](artifacts.md)
* **AdministrativeGender**

## ValueSet: AdministrativeGender 

| | |
| :--- | :--- |
| *URL officiel*:https://interop.esante.gouv.fr/ig/fhir/fr/ValueSet/jdv-hl7-v3-AdministrativeGender-cisis | *Version*:0.1.0 |
| Active à partir de 2025-12-16 | *Nom computable*:AdministrativeGender |
| *Autres identifiants:*OID:2.16.840.1.113883.1.11.1 | |

 
AdministrativeGender 

 **References** 

Ce jeu de valeurs n'est pas utilisé ici ; il peut être utilisé autre part (par exemple dans les spécifications et / ou implémentations qui utilisent ce contenu)

### Définition logique (CLD)

 

### Expansion

-------

 [Description du (des) tableau(x) ci-dessus](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "jdv-hl7-v3-AdministrativeGender-cisis",
  "meta" : {
    "versionId" : "6",
    "lastUpdated" : "2025-12-17T15:42:39.378+01:00",
    "profile" : ["http://hl7.org/fhir/StructureDefinition/shareablevalueset|4.0.1"]
  },
  "extension" : [{
    "url" : "http://hl7.org/fhir/StructureDefinition/resource-effectivePeriod",
    "valuePeriod" : {
      "start" : "2010-01-01T00:00:00+01:00"
    }
  }],
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/ValueSet/jdv-hl7-v3-AdministrativeGender-cisis",
  "identifier" : [{
    "system" : "urn:ietf:rfc:3986",
    "value" : "urn:oid:2.16.840.1.113883.1.11.1"
  }],
  "version" : "0.1.0",
  "name" : "AdministrativeGender",
  "title" : "AdministrativeGender",
  "status" : "active",
  "experimental" : false,
  "date" : "2025-12-16T14:18:38+01:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "AdministrativeGender",
  "jurisdiction" : [{
    "coding" : [{
      "system" : "urn:iso:std:iso:3166",
      "code" : "FR",
      "display" : "France"
    }]
  }],
  "compose" : {
    "include" : [{
      "system" : "http://terminology.hl7.org/CodeSystem/v3-AdministrativeGender",
      "version" : "4.0.0",
      "concept" : [{
        "code" : "F"
      },
      {
        "code" : "M"
      },
      {
        "code" : "UN"
      }]
    },
    {
      "system" : "http://terminology.hl7.org/CodeSystem/v3-orderableDrugForm",
      "version" : "4.0.0",
      "concept" : [{
        "code" : "DROP"
      }]
    }]
  }
}

```
