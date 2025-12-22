# DaysOfWeek - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **DaysOfWeek**

## CodeSystem: DaysOfWeek 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-days-of-week | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:DaysOfWeek |

 
The days of the week. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-days-of-week",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-days-of-week",
  "version" : "0.1.0",
  "name" : "DaysOfWeek",
  "title" : "DaysOfWeek",
  "status" : "active",
  "date" : "2025-12-22T14:22:23+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "The days of the week.",
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
  "caseSensitive" : false,
  "content" : "supplement",
  "supplements" : "http://hl7.org/fhir/days-of-week|4.0.1",
  "concept" : [
    {
      "code" : "mon",
      "display" : "måndag"
    },
    {
      "code" : "tue",
      "display" : "tisdag"
    },
    {
      "code" : "wed",
      "display" : "onsdag"
    },
    {
      "code" : "thu",
      "display" : "torsdag"
    },
    {
      "code" : "fri",
      "display" : "fredag"
    },
    {
      "code" : "sat",
      "display" : "lördag"
    },
    {
      "code" : "sun",
      "display" : "söndag"
    }
  ]
}

```
