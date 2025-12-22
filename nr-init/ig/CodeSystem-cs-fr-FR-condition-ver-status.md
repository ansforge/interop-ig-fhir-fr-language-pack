# ConditionVerificationStatus - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ConditionVerificationStatus**

## CodeSystem: ConditionVerificationStatus 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-condition-ver-status | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ConditionVerificationStatus |
| **Copyright/Legal**: This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license | |

 
The verification status to support or decline the clinical status of the condition or diagnosis. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-condition-ver-status",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-condition-ver-status",
  "version" : "0.1.0",
  "name" : "ConditionVerificationStatus",
  "title" : "ConditionVerificationStatus",
  "status" : "active",
  "date" : "2025-12-22T17:43:16+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "The verification status to support or decline the clinical status of the condition or diagnosis.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/condition-ver-status|2.0.1",
  "concept" : [
    {
      "code" : "unconfirmed",
      "display" : "Non confirmé"
    },
    {
      "code" : "confirmed",
      "display" : "Confirmé"
    },
    {
      "code" : "refuted",
      "display" : "Réfuté"
    }
  ]
}

```
