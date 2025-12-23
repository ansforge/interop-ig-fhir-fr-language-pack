# TimingEvent - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **TimingEvent**

## CodeSystem: TimingEvent 

| | |
| :--- | :--- |
| **:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-TimingEvent | **:0.1.0 |
| Active | **:TimingEvent |
| **: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
**** MISSING DESCRIPTION **** 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)

-------

 . 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-TimingEvent",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-TimingEvent",
  "version" : "0.1.0",
  "name" : "TimingEvent",
  "title" : "TimingEvent",
  "status" : "active",
  "date" : "2025-12-23T09:21:12+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "**** MISSING DESCRIPTION ****",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-TimingEvent|3.0.0",
  "concept" : [
    {
      "code" : "AC",
      "display" : "Avant le repas"
    },
    {
      "code" : "ACD",
      "display" : "Avant le déjeuner"
    },
    {
      "code" : "ACM",
      "display" : "Avant le petit-déjeuner"
    },
    {
      "code" : "ACV",
      "display" : "Avant le dîner"
    },
    {
      "code" : "C",
      "display" : "Pendant les repas"
    },
    {
      "code" : "CD",
      "display" : "Pendant le déjeuner"
    },
    {
      "code" : "CM",
      "display" : "Pendant le petit-déjeuner"
    },
    {
      "code" : "CV",
      "display" : "Pendant le dîner"
    },
    {
      "code" : "HS",
      "display" : "Au coucher"
    },
    {
      "code" : "IC",
      "display" : "Entre les repas"
    },
    {
      "code" : "ICD",
      "display" : "Entre le déjeuner et le dîner"
    },
    {
      "code" : "ICM",
      "display" : "Entre le petit-déjeûner et le déjeûner"
    },
    {
      "code" : "ICV",
      "display" : "Entre le diner et le coucher"
    },
    {
      "code" : "PC",
      "display" : "Après le repas"
    },
    {
      "code" : "PCD",
      "display" : "Après le déjeuner"
    },
    {
      "code" : "PCM",
      "display" : "Après le petit-déjeuner"
    },
    {
      "code" : "PCV",
      "display" : "Après le dîner"
    },
    {
      "code" : "WAKE",
      "display" : "Au réveil"
    }
  ]
}

```
