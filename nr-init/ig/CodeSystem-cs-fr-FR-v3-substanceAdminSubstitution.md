# SubstanceAdminSubstitution - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **SubstanceAdminSubstitution**

## CodeSystem: SubstanceAdminSubstitution 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-substanceAdminSubstitution | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:SubstanceAdminSubstitution |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
Identifies what sort of change is permitted or has occurred between the therapy that was ordered and the therapy that was/will be provided. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-substanceAdminSubstitution",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-substanceAdminSubstitution",
  "version" : "0.1.0",
  "name" : "SubstanceAdminSubstitution",
  "title" : "Substance Admin Substitution",
  "status" : "active",
  "date" : "2025-12-22T17:37:51+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "Identifies what sort of change is permitted or has occurred between the therapy that was ordered and the therapy that was/will be provided.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution|3.0.0",
  "concept" : [
    {
      "code" : "N",
      "display" : "Aucune substitution permise"
    },
    {
      "code" : "G",
      "display" : "Substitution autorisée par un produit générique"
    }
  ]
}

```
