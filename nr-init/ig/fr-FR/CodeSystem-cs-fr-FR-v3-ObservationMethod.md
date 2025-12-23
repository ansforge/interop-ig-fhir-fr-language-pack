# ObservationMethod - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ObservationMethod**

## CodeSystem: ObservationMethod 

| | |
| :--- | :--- |
| **:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ObservationMethod | **:0.1.0 |
| Active | **:ObservationMethod |
| **: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
A code that provides additional detail about the means or technique used to ascertain the observation. 
**Examples:**Blood pressure measurement method: arterial puncture vs. sphygmomanometer (Riva-Rocci), sitting vs. supine position, etc. 
**OpenIssue:**Description copied from Concept Domain of same name. Must be verified. Note that the Domain has a full discussion about use of the attribute and constraining that is not appropriate for the code system description. Needs to be improved. 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)

-------

 . 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-ObservationMethod",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ObservationMethod",
  "version" : "0.1.0",
  "name" : "ObservationMethod",
  "title" : "ObservationMethod",
  "status" : "active",
  "date" : "2025-12-23T09:21:12+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "A code that provides additional detail about the means or technique used to ascertain the observation.\r\n\r\n*Examples:* Blood pressure measurement method: arterial puncture vs. sphygmomanometer (Riva-Rocci), sitting vs. supine position, etc.\r\n\r\n*OpenIssue:* Description copied from Concept Domain of same name. Must be verified. Note that the Domain has a full discussion about use of the attribute and constraining that is not appropriate for the code system description. Needs to be improved.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-ObservationMethod|3.0.0",
  "concept" : [
    {
      "code" : "ALGM",
      "display" : "Algorythme"
    },
    {
      "code" : "BYCL",
      "display" : "Analyse stastistique Bayésienne"
    },
    {
      "code" : "PCR",
      "display" : "PCR"
    },
    {
      "code" : "VDOC",
      "display" : "Vérification à partir d'un document"
    },
    {
      "code" : "VREG",
      "display" : "Vérification par requête électronique"
    },
    {
      "code" : "VTOKEN",
      "display" : "Vérification au moyen d'un jeton électronique"
    },
    {
      "code" : "VVOICE",
      "display" : "Vérification par voie orale"
    }
  ]
}

```
