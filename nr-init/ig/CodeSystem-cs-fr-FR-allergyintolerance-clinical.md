# AllergyIntoleranceClinicalStatusCodes - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **AllergyIntoleranceClinicalStatusCodes**

## CodeSystem: AllergyIntoleranceClinicalStatusCodes 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-allergyintolerance-clinical | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:AllergyIntoleranceClinicalStatusCodes |
| **Copyright/Legal**: This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license | |

 
Preferred value set for AllergyIntolerance Clinical Status. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-allergyintolerance-clinical",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-allergyintolerance-clinical",
  "version" : "0.1.0",
  "name" : "AllergyIntoleranceClinicalStatusCodes",
  "title" : "AllergyIntolerance Clinical Status Codes",
  "status" : "active",
  "date" : "2025-12-22T17:10:15+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "Preferred value set for AllergyIntolerance Clinical Status.",
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
  "copyright" : "This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license",
  "caseSensitive" : false,
  "content" : "supplement",
  "supplements" : "http://terminology.hl7.org/CodeSystem/allergyintolerance-clinical|1.0.1",
  "concept" : [
    {
      "code" : "active",
      "display" : "Actif"
    },
    {
      "code" : "inactive",
      "display" : "Inactif"
    },
    {
      "code" : "resolved",
      "display" : "Résolu"
    }
  ]
}

```
