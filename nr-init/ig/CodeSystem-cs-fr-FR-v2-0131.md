# ContactRole2 - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ContactRole2**

## CodeSystem: ContactRole2 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v2-0131 | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ContactRole2 |
| **Copyright/Legal**: This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
Code system of concepts which specify a relationship role that the next of kin/associated parties plays with regard to the patient. Also used in referrals, for example, it may be necessary to identify the contact representative at the clinic that sent a referral. Used in HL7 Version 2 messaging in the NK1 and CTD segments after 2.5, when it replace 2.16.840.1.113883.18.57. 

 
Underlying Master Code System for V2 table 0131 (Contact Role) 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v2-0131",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v2-0131",
  "version" : "0.1.0",
  "name" : "ContactRole2",
  "title" : "contactRole2",
  "status" : "active",
  "date" : "2025-12-22T14:16:52+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "Code system of concepts which specify a relationship role that the next of kin/associated parties plays with regard to the patient. Also used in referrals, for example, it may be necessary to identify the contact representative at the clinic that sent a referral. Used in HL7 Version 2 messaging in the NK1 and CTD segments after 2.5, when it replace 2.16.840.1.113883.18.57.",
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
  "purpose" : "Underlying Master Code System for V2 table 0131 (Contact Role)",
  "copyright" : "This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html",
  "caseSensitive" : false,
  "content" : "supplement",
  "supplements" : "http://terminology.hl7.org/CodeSystem/v2-0131|3.0.0",
  "concept" : [
    {
      "code" : "BP",
      "display" : "kontaktperson fakturering"
    },
    {
      "code" : "CP",
      "display" : "kontaktperson"
    },
    {
      "code" : "EP",
      "display" : "kontaktperson nöd"
    },
    {
      "code" : "PR"
    },
    {
      "code" : "E",
      "display" : "arbetsgivare"
    },
    {
      "code" : "C",
      "display" : "nödkontakt"
    },
    {
      "code" : "F"
    },
    {
      "code" : "I",
      "display" : "försäkringsbolag"
    },
    {
      "code" : "N",
      "display" : "anhörig"
    },
    {
      "code" : "S"
    },
    {
      "code" : "O",
      "display" : "annan"
    },
    {
      "code" : "U",
      "display" : "okänd"
    }
  ]
}

```
