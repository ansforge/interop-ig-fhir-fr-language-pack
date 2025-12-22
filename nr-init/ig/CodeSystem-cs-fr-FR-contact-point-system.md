# ContactPointSystem - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ContactPointSystem**

## CodeSystem: ContactPointSystem 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-contact-point-system | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ContactPointSystem |

 
Telecommunications form for contact point. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-contact-point-system",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-contact-point-system",
  "version" : "0.1.0",
  "name" : "ContactPointSystem",
  "title" : "ContactPointSystem",
  "status" : "active",
  "date" : "2025-12-22T14:16:52+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "Telecommunications form for contact point.",
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
  "caseSensitive" : false,
  "content" : "supplement",
  "supplements" : "http://hl7.org/fhir/contact-point-system|4.0.1",
  "concept" : [
    {
      "code" : "phone",
      "display" : "telefon"
    },
    {
      "code" : "fax",
      "display" : "fax"
    },
    {
      "code" : "email",
      "display" : "e-post"
    },
    {
      "code" : "pager",
      "display" : "personsökare"
    },
    {
      "code" : "url",
      "display" : "URL"
    },
    {
      "code" : "sms",
      "display" : "SMS"
    },
    {
      "code" : "other",
      "display" : "annat"
    }
  ]
}

```
