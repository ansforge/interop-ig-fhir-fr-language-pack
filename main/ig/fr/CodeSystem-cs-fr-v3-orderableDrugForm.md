# OrderableDrugForm - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Résumé des artefacts**](artifacts.md)
* **OrderableDrugForm**

## CodeSystem: OrderableDrugForm 

| | |
| :--- | :--- |
| *URL officiel*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-v3-orderableDrugForm | *Version*:0.1.0 |
| Active à partir de 2026-05-05 | *Nom computable*:OrderableDrugForm |
| **Droit d'auteur/juridique**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
**OpenIssue:** Missing description. 

Ce système de codes est référencé dans la définition des ensembles de valeurs suivants :

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)

-------

 [Description du (des) tableau(x) ci-dessus](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-v3-orderableDrugForm",
  "language" : "fr",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-v3-orderableDrugForm",
  "version" : "0.1.0",
  "name" : "OrderableDrugForm",
  "title" : "Orderable Drug Form",
  "status" : "active",
  "date" : "2026-05-05T15:18:46+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "*OpenIssue:* Missing description.",
  "jurisdiction" : [{
    "coding" : [{
      "system" : "urn:iso:std:iso:3166",
      "code" : "FR",
      "display" : "France"
    }]
  }],
  "copyright" : "This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html",
  "caseSensitive" : false,
  "content" : "supplement",
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-orderableDrugForm|4.0.0",
  "concept" : [{
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
  }]
}

```
