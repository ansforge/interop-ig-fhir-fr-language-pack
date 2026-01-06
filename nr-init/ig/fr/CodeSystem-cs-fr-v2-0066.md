# EmploymentStatus - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Résumé des artefacts**](artifacts.md)
* **EmploymentStatus**

## CodeSystem: EmploymentStatus 

| | |
| :--- | :--- |
| *URL officiel*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-v2-0066 | *Version*:0.1.0 |
| Active à partir de 2026-01-06 | *Nom computable*:EmploymentStatus |
| **Droit d'auteur/juridique**: This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
HL7-defined code system of concepts which specify an employment status of a person. Used in HL7 Version 2 messaging in the GT1 segment. 

Ce système de codes est référencé dans la définition des ensembles de valeurs suivants :

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)

-------

 [Description du (des) tableau(x) ci-dessus](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-v2-0066",
  "language" : "fr",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-v2-0066",
  "version" : "0.1.0",
  "name" : "EmploymentStatus",
  "title" : "employmentStatus",
  "status" : "active",
  "date" : "2026-01-06T09:35:23+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "HL7-defined code system of concepts which specify an employment status of a person. Used in HL7 Version 2 messaging in the GT1 segment.",
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
  "purpose" : "Underlying Master Code System for V2 table 0066 (Employment Status)",
  "copyright" : "This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html",
  "caseSensitive" : false,
  "content" : "supplement",
  "supplements" : "http://terminology.hl7.org/CodeSystem/v2-0066|3.0.0",
  "concept" : [
    {
      "code" : "1",
      "display" : "Employé à temps plein"
    },
    {
      "code" : "2",
      "display" : "Employé à temps partiel"
    },
    {
      "code" : "3",
      "display" : "Sans emploi"
    },
    {
      "code" : "4",
      "display" : "Auto-entrepreuneur"
    },
    {
      "code" : "5",
      "display" : "Retraité"
    },
    {
      "code" : "6",
      "display" : "En service militaire actif"
    },
    {
      "code" : "9",
      "display" : "Statut d'emploi inconnu"
    },
    {
      "code" : "C",
      "display" : "Contrat journalier"
    },
    {
      "code" : "L",
      "display" : "Congé (par exemple, congé familial, congé sabbatique, etc.)"
    },
    {
      "code" : "T",
      "display" : "Temporairement sans emploi"
    },
    {
      "code" : "O",
      "display" : "Autre"
    }
  ]
}

```
