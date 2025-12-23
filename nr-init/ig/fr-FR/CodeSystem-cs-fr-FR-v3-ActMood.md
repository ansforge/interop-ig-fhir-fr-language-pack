# ActMood - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ActMood**

## CodeSystem: ActMood 

| | |
| :--- | :--- |
| **:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ActMood | **:0.1.0 |
| Active | **:ActMood |
| **: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
OpenIssue: In Ballot 2009May, a strong Negative vote was lodged against several of the concept definitions in the vocabulary used for Act.moodCode. The vote was found "Persuasive With Mod", with the understanding that M and M would undertake a detailed review of these concept definitions for a future release of the RIM. 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)

-------

 . 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-ActMood",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ActMood",
  "version" : "0.1.0",
  "name" : "ActMood",
  "title" : "ActMood",
  "status" : "active",
  "date" : "2025-12-23T09:21:12+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "OpenIssue: In Ballot 2009May, a strong Negative vote was lodged against several of the concept definitions in the vocabulary used for Act.moodCode. The vote was found \"Persuasive With Mod\", with the understanding that M and M would undertake a detailed review of these concept definitions for a future release of the RIM.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-ActMood|3.0.0",
  "concept" : [
    {
      "code" : "DEF",
      "display" : "Définition"
    },
    {
      "code" : "PERM",
      "display" : "Permission"
    },
    {
      "code" : "SLOT",
      "display" : "Possible sur la période spécifiée"
    },
    {
      "code" : "EVN",
      "display" : "Réalisé"
    },
    {
      "code" : "INT",
      "display" : "Prévu"
    },
    {
      "code" : "ARQ",
      "display" : "Prévu mais non confirmé"
    },
    {
      "code" : "PERMRQ",
      "display" : "Demande d'autorisation"
    },
    {
      "code" : "RQO",
      "display" : "Demande"
    },
    {
      "code" : "PRP",
      "display" : "Proposition"
    },
    {
      "code" : "RMD",
      "display" : "Recommandation"
    },
    {
      "code" : "PRMS",
      "display" : "Planifié et confirmé"
    },
    {
      "code" : "APT",
      "display" : "Date et lieu confirmé"
    },
    {
      "code" : "EXPEC",
      "display" : "Attendu"
    },
    {
      "code" : "GOL",
      "display" : "But"
    },
    {
      "code" : "RSK",
      "display" : "Risque"
    },
    {
      "code" : "OPT",
      "display" : "Option"
    }
  ]
}

```
