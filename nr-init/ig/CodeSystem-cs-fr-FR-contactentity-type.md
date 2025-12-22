# ContactEntityType - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ContactEntityType**

## CodeSystem: ContactEntityType 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-contactentity-type | *Version*:0.1.0 |
| Draft as of 2025-12-22 | *Computable Name*:ContactEntityType |
| **Copyright/Legal**: This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
This example value set defines a set of codes that can be used to indicate the purpose for which you would contact a contact party. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-contactentity-type",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-contactentity-type",
  "version" : "0.1.0",
  "name" : "ContactEntityType",
  "title" : "Contact entity type",
  "status" : "draft",
  "date" : "2025-12-22T14:22:23+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "This example value set defines a set of codes that can be used to indicate the purpose for which you would contact a contact party.",
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
  "copyright" : "This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html",
  "caseSensitive" : false,
  "content" : "supplement",
  "supplements" : "http://terminology.hl7.org/CodeSystem/contactentity-type|1.0.0",
  "concept" : [
    {
      "code" : "BILL",
      "display" : "fakturering"
    },
    {
      "code" : "ADMIN",
      "display" : "administration"
    },
    {
      "code" : "HR",
      "display" : "personalärenden"
    },
    {
      "code" : "PAYOR",
      "display" : "ersättning"
    },
    {
      "code" : "PATINF",
      "display" : "patient"
    },
    {
      "code" : "PRESS",
      "display" : "media"
    }
  ]
}

```
