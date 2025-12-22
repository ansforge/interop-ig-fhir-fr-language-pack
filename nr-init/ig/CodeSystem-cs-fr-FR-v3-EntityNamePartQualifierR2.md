# EntityNamePartQualifierR2 - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **EntityNamePartQualifierR2**

## CodeSystem: EntityNamePartQualifierR2 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-EntityNamePartQualifierR2 | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:EntityNamePartQualifierR2 |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
**Description:**The qualifier is a set of codes each of which specifies a certain subcategory of the name part in addition to the main name part type. For example, a given name may be flagged as a nickname, a family name may be a pseudonym or a name of public records. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-EntityNamePartQualifierR2",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-EntityNamePartQualifierR2",
  "version" : "0.1.0",
  "name" : "EntityNamePartQualifierR2",
  "title" : "EntityNamePartQualifierR2",
  "status" : "active",
  "date" : "2025-12-22T14:22:23+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "**Description:**The qualifier is a set of codes each of which specifies a certain subcategory of the name part in addition to the main name part type. For example, a given name may be flagged as a nickname, a family name may be a pseudonym or a name of public records.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-EntityNamePartQualifierR2|3.0.0",
  "concept" : [
    {
      "code" : "AD"
    },
    {
      "code" : "SP",
      "display" : "make/maka"
    },
    {
      "code" : "BR"
    },
    {
      "code" : "CL",
      "display" : "tilltalsnamn"
    },
    {
      "code" : "IN",
      "display" : "initial"
    },
    {
      "code" : "LS"
    },
    {
      "code" : "MID",
      "display" : "mellannamn"
    },
    {
      "code" : "PFX"
    },
    {
      "code" : "PharmaceuticalEntityNamePartQualifiers"
    },
    {
      "code" : "CON"
    },
    {
      "code" : "DEV"
    },
    {
      "code" : "FLAV"
    },
    {
      "code" : "FORMUL"
    },
    {
      "code" : "FRM"
    },
    {
      "code" : "INV"
    },
    {
      "code" : "POPUL"
    },
    {
      "code" : "SCI"
    },
    {
      "code" : "STR"
    },
    {
      "code" : "TIME"
    },
    {
      "code" : "TMK"
    },
    {
      "code" : "USE"
    },
    {
      "code" : "SFX"
    },
    {
      "code" : "TitleStyles"
    },
    {
      "code" : "AC"
    },
    {
      "code" : "HON"
    },
    {
      "code" : "HOM"
    },
    {
      "code" : "NB"
    },
    {
      "code" : "PR"
    }
  ]
}

```
