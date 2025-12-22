# ConditionClinicalStatusCodes - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ConditionClinicalStatusCodes**

## CodeSystem: ConditionClinicalStatusCodes 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-condition-clinical | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ConditionClinicalStatusCodes |
| **Copyright/Legal**: This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
Preferred value set for Condition Clinical Status. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-condition-clinical",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-condition-clinical",
  "version" : "0.1.0",
  "name" : "ConditionClinicalStatusCodes",
  "title" : "Condition Clinical Status Codes",
  "status" : "active",
  "date" : "2025-12-22T17:32:51+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "Preferred value set for Condition Clinical Status.",
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
  "copyright" : "This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html",
  "caseSensitive" : false,
  "content" : "supplement",
  "supplements" : "http://terminology.hl7.org/CodeSystem/condition-clinical|3.0.0",
  "concept" : [
    {
      "code" : "active",
      "display" : "Actif"
    },
    {
      "code" : "recurrence",
      "display" : "Récurrent"
    },
    {
      "code" : "relapse",
      "display" : "Rechute"
    },
    {
      "code" : "inactive",
      "display" : "Inactif"
    },
    {
      "code" : "remission",
      "display" : "En rémission"
    },
    {
      "code" : "resolved",
      "display" : "Résolu"
    }
  ]
}

```
