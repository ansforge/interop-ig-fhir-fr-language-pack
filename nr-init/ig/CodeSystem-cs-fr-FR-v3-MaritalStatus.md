# MaritalStatus - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **MaritalStatus**

## CodeSystem: MaritalStatus 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-MaritalStatus | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:MaritalStatus |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
* * * No description supplied * * * 
**Open Issue:**The specific meanings of these codes can vary somewhat by jurisdiction and implementation so caution should be used when determining equivalency. 
**Open Issue:**fixing and completion of the hierarchy and proper good definitions of all the concepts is badly needed. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-MaritalStatus",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-MaritalStatus",
  "version" : "0.1.0",
  "name" : "MaritalStatus",
  "title" : "MaritalStatus",
  "status" : "active",
  "date" : "2025-12-22T14:22:23+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "\\* \\* \\* No description supplied \\* \\* \\*\r\n\r\n*Open Issue:* The specific meanings of these codes can vary somewhat by jurisdiction and implementation so caution should be used when determining equivalency.\r\n\r\n*Open Issue:* fixing and completion of the hierarchy and proper good definitions of all the concepts is badly needed.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-MaritalStatus|3.0.0",
  "concept" : [
    {
      "code" : "A"
    },
    {
      "code" : "D",
      "display" : "skild"
    },
    {
      "code" : "I"
    },
    {
      "code" : "L"
    },
    {
      "code" : "M",
      "display" : "gift"
    },
    {
      "code" : "C"
    },
    {
      "code" : "P"
    },
    {
      "code" : "T"
    },
    {
      "code" : "U",
      "display" : "ogift"
    },
    {
      "code" : "S"
    },
    {
      "code" : "W",
      "display" : "änka/änkling"
    }
  ]
}

```
