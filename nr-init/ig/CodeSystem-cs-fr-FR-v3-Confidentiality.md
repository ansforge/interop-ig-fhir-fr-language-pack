# Confidentiality - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Confidentiality**

## CodeSystem: Confidentiality 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-Confidentiality | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:Confidentiality |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
A set of codes specifying the security classification of acts and roles in accordance with the definition for concept domain "Confidentiality". 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-Confidentiality",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-Confidentiality",
  "version" : "0.1.0",
  "name" : "Confidentiality",
  "title" : "Confidentiality",
  "status" : "active",
  "date" : "2025-12-22T17:17:12+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "A set of codes specifying the security classification of acts and roles in accordance with the definition for concept domain \"Confidentiality\".",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-Confidentiality|3.0.0",
  "concept" : [
    {
      "code" : "L",
      "display" : "Bas"
    },
    {
      "code" : "M",
      "display" : "Modéré"
    },
    {
      "code" : "N",
      "display" : "Normal"
    },
    {
      "code" : "R",
      "display" : "Restreint"
    },
    {
      "code" : "U",
      "display" : "Non restreint"
    },
    {
      "code" : "V",
      "display" : "Très restreint"
    }
  ]
}

```
