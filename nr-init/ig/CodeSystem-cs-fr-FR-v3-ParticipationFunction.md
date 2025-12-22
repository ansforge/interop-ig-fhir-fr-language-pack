# ParticipationFunction - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ParticipationFunction**

## CodeSystem: ParticipationFunction 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ParticipationFunction | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ParticipationFunction |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
This code is used to specify the exact function an actor had in a service in all necessary detail. This domain may include local extensions (CWE). 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-ParticipationFunction",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ParticipationFunction",
  "version" : "0.1.0",
  "name" : "ParticipationFunction",
  "title" : "ParticipationFunction",
  "status" : "active",
  "date" : "2025-12-22T17:21:11+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "This code is used to specify the exact function an actor had in a service in all necessary detail. This domain may include local extensions (CWE).",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-ParticipationFunction|3.0.0",
  "concept" : [
    {
      "code" : "ADMPHYS",
      "display" : "Responsable de l'admission"
    },
    {
      "code" : "ATTPHYS",
      "display" : "Référent - Responsable du patient dans la structure de soins"
    },
    {
      "code" : "DISPHYS",
      "display" : "Responsable de la sortie"
    },
    {
      "code" : "PCP",
      "display" : "Médecin traitant"
    }
  ]
}

```
