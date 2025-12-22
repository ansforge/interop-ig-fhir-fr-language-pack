# ActPriority - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ActPriority**

## CodeSystem: ActPriority 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ActPriority | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ActPriority |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
A set of codes (e.g., for routine, emergency), specifying the urgency under which the Act happened, can happen, is happening, is intended to happen, or is requested/demanded to happen. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-ActPriority",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ActPriority",
  "version" : "0.1.0",
  "name" : "ActPriority",
  "title" : "ActPriority",
  "status" : "active",
  "date" : "2025-12-22T17:43:16+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "A set of codes (e.g., for routine, emergency), specifying the urgency under which the Act happened, can happen, is happening, is intended to happen, or is requested/demanded to happen.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-ActPriority|3.0.0",
  "concept" : [
    {
      "code" : "A",
      "display" : "Aussi vite que possible"
    },
    {
      "code" : "CR",
      "display" : "A contacter dès que les résultats sont disponibles"
    },
    {
      "code" : "EL",
      "display" : "Bénéfique pour le patient mais pas essentiel pour sa survie"
    },
    {
      "code" : "EM",
      "display" : "Très urgent"
    },
    {
      "code" : "P",
      "display" : "A réaliser avant l'intervention"
    },
    {
      "code" : "PRN",
      "display" : "Si nécessaire"
    },
    {
      "code" : "R",
      "display" : "A réaliser aux heures ouvrées"
    },
    {
      "code" : "RR",
      "display" : "Compte-rendu urgent"
    },
    {
      "code" : "S",
      "display" : "Immédiatement"
    },
    {
      "code" : "T",
      "display" : "Plannification à respecter"
    },
    {
      "code" : "UD",
      "display" : "Médicament à utiliser selon les directives du prescripteur"
    },
    {
      "code" : "UR",
      "display" : "Urgent"
    }
  ]
}

```
