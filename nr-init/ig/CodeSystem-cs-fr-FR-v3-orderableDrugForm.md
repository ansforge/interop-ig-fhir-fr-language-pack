# OrderableDrugForm - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **OrderableDrugForm**

## CodeSystem: OrderableDrugForm 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-orderableDrugForm | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:OrderableDrugForm |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
**OpenIssue:**Missing description. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-orderableDrugForm",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-orderableDrugForm",
  "version" : "0.1.0",
  "name" : "OrderableDrugForm",
  "title" : "Orderable Drug Form",
  "status" : "active",
  "date" : "2025-12-22T17:37:51+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "*OpenIssue:* Missing description.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-orderableDrugForm|3.0.0",
  "concept" : [
    {
      "code" : "APPFUL",
      "display" : "Dose d'applicateur"
    },
    {
      "code" : "PUFF",
      "display" : "Bouffée"
    },
    {
      "code" : "SCOOP",
      "display" : "Cuillerées"
    },
    {
      "code" : "SPRY",
      "display" : "Pulvérisations"
    },
    {
      "code" : "DROP",
      "display" : "Gouttes"
    },
    {
      "code" : "NDROP",
      "display" : "Gouttes nasales"
    },
    {
      "code" : "OPDROP",
      "display" : "Gouttes ophtalmiques"
    },
    {
      "code" : "ORDROP",
      "display" : "Gouttes orales"
    },
    {
      "code" : "OTDROP",
      "display" : "Gouttes auriculaires"
    }
  ]
}

```
