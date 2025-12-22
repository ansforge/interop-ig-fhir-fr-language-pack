# ActStatus - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ActStatus**

## CodeSystem: ActStatus 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ActStatus | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ActStatus |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
Codes representing the defined possible states of an Act, as defined by the Act class state machine. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-ActStatus",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ActStatus",
  "version" : "0.1.0",
  "name" : "ActStatus",
  "title" : "ActStatus",
  "status" : "active",
  "date" : "2025-12-22T17:32:51+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "Codes representing the defined possible states of an Act, as defined by the Act class state machine.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-ActStatus|3.0.0",
  "concept" : [
    {
      "code" : "aborted",
      "display" : "Arrêté (après son lancement)"
    },
    {
      "code" : "active",
      "display" : "Actif (en cours ou à venir)"
    },
    {
      "code" : "cancelled",
      "display" : "Annulé (avant son lancement)"
    },
    {
      "code" : "completed",
      "display" : "Terminé"
    },
    {
      "code" : "held",
      "display" : "En attente (avant son lancement)"
    },
    {
      "code" : "new",
      "display" : "En préparation"
    },
    {
      "code" : "suspended",
      "display" : "Suspendu (au cours de sa réalisation)"
    }
  ]
}

```
