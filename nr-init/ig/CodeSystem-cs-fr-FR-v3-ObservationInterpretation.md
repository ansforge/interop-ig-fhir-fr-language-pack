# ObservationInterpretation - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ObservationInterpretation**

## CodeSystem: ObservationInterpretation 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ObservationInterpretation | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ObservationInterpretation |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
One or more codes providing a rough qualitative interpretation of the observation, such as "normal" / "abnormal", "low" / "high", "better" / "worse", "resistant" / "susceptible", "expected" / "not expected". The value set is intended to be for ANY use where coded representation of an interpretation is needed. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-ObservationInterpretation",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ObservationInterpretation",
  "version" : "0.1.0",
  "name" : "ObservationInterpretation",
  "title" : "ObservationInterpretation",
  "status" : "active",
  "date" : "2025-12-22T17:37:51+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "One or more codes providing a rough qualitative interpretation of the observation, such as \"normal\" / \"abnormal\", \"low\" / \"high\", \"better\" / \"worse\", \"resistant\" / \"susceptible\", \"expected\" / \"not expected\". The value set is intended to be for ANY use where coded representation of an interpretation is needed.",
  "jurisdiction" : [
    {
      "coding" : [
        {
          "system" : "urn:iso:std:iso:3166",
          "code" : "FR",
          "display" : "FRANCE"
        }
      ]
    }
  ],
  "copyright" : "This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html",
  "caseSensitive" : false,
  "content" : "supplement",
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-ObservationInterpretation|3.0.0",
  "concept" : [
    {
      "code" : "<",
      "display" : "Inférieur à la limite de détection"
    },
    {
      "code" : ">",
      "display" : "Supérieur à la limite maximale de mesure"
    },
    {
      "code" : "A",
      "display" : "Anormal"
    },
    {
      "code" : "AA",
      "display" : "Très anormal, alerte"
    },
    {
      "code" : "B",
      "display" : "Amélioration"
    },
    {
      "code" : "CAR",
      "display" : "Porteur d'une forme altérée d'un gène"
    },
    {
      "code" : "D",
      "display" : "Diminution significative par rapport au résultat antérieur"
    },
    {
      "code" : "DET",
      "display" : "Détecté"
    },
    {
      "code" : "E",
      "display" : "Équivoque"
    },
    {
      "code" : "EX",
      "display" : "Hors seuils"
    },
    {
      "code" : "EXP",
      "display" : "Attendu"
    },
    {
      "code" : "H",
      "display" : "Anormalement haut"
    },
    {
      "code" : "HH",
      "display" : "Très anormalement haut, alerte"
    },
    {
      "code" : "HU",
      "display" : "Significativement haut"
    },
    {
      "code" : "HX",
      "display" : "Hors seuil supérieur"
    },
    {
      "code" : "I",
      "display" : "Intermédiaire"
    },
    {
      "code" : "IE",
      "display" : "Preuves insuffisantes"
    },
    {
      "code" : "IND",
      "display" : "Indéterminé"
    },
    {
      "code" : "L",
      "display" : "Anormalement bas"
    },
    {
      "code" : "LL",
      "display" : "Très anormalement bas, alerte"
    },
    {
      "code" : "LU",
      "display" : "Significativement bas"
    },
    {
      "code" : "LX",
      "display" : "Hors seuil inférieur"
    },
    {
      "code" : "N",
      "display" : "Normal"
    },
    {
      "code" : "NCL",
      "display" : "Pas de standard défini"
    },
    {
      "code" : "ND",
      "display" : "Non détecté"
    },
    {
      "code" : "NEG",
      "display" : "Négatif"
    },
    {
      "code" : "NR",
      "display" : "Non réactif"
    },
    {
      "code" : "NS",
      "display" : "Non sensible"
    },
    {
      "code" : "POS",
      "display" : "Positif"
    },
    {
      "code" : "R",
      "display" : "Résistant"
    },
    {
      "code" : "RR",
      "display" : "Réactif"
    },
    {
      "code" : "S",
      "display" : "Sensible"
    },
    {
      "code" : "SDD",
      "display" : "Sensible à forte dose"
    },
    {
      "code" : "SYN-R",
      "display" : "Synergie - résistant"
    },
    {
      "code" : "SYN-S",
      "display" : "Synergie - sensible"
    },
    {
      "code" : "U",
      "display" : "Augmentation significative par rapport au résultat antérieur"
    },
    {
      "code" : "UNE",
      "display" : "Inattendu"
    },
    {
      "code" : "W",
      "display" : "Dégradation"
    },
    {
      "code" : "WR",
      "display" : "Faiblement réactif"
    }
  ]
}

```
