# ObservationValue - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ObservationValue**

## CodeSystem: ObservationValue 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ObservationValue | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ObservationValue |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
This code system covers all concepts of HL7-defined values for the Observation value element, when it has a coded datatype. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-ObservationValue",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ObservationValue",
  "version" : "0.1.0",
  "name" : "ObservationValue",
  "title" : "ObservationValue",
  "status" : "active",
  "date" : "2025-12-22T17:21:11+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "This code system covers all concepts of HL7-defined values for the Observation value element, when it has a coded datatype.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-ObservationValue|4.0.0",
  "concept" : [
    {
      "code" : "DS",
      "display" : "Journée (par exemple : entre 6h et 18h)"
    },
    {
      "code" : "EMS",
      "display" : "Matin (entre 2h et 14h)"
    },
    {
      "code" : "ES",
      "display" : "Après-midi (entre 14h et minuit)"
    },
    {
      "code" : "NS",
      "display" : "Nuit (entre 21h et 8h)"
    },
    {
      "code" : "RSWN",
      "display" : "Variable (journées, soirées, avec parfois des nuits)"
    },
    {
      "code" : "RSWON",
      "display" : "Variable (journées, soirées, sans nuits ni soirées)"
    },
    {
      "code" : "SS",
      "display" : "Journée avec coupure de 2 à 4 heures."
    },
    {
      "code" : "VLS",
      "display" : "Horaires de longue durée (17h ou plus)"
    },
    {
      "code" : "VS",
      "display" : "Irrégulier avec information à court terme"
    },
    {
      "code" : "Employed",
      "display" : "En activité"
    },
    {
      "code" : "NotInLaborForce",
      "display" : "Inactif"
    },
    {
      "code" : "Unemployed",
      "display" : "Sans activité"
    }
  ]
}

```
