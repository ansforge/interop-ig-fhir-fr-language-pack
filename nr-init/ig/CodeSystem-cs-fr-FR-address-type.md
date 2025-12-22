# AddressType - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **AddressType**

## CodeSystem: AddressType 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-address-type | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:AddressType |

 
The type of an address (physical / postal). 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-address-type",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-address-type",
  "version" : "0.1.0",
  "name" : "AddressType",
  "title" : "AddressType",
  "status" : "active",
  "date" : "2025-12-22T14:16:52+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "The type of an address (physical / postal).",
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
  "supplements" : "http://hl7.org/fhir/address-type|4.0.1",
  "concept" : [
    {
      "code" : "postal",
      "display" : "utdelningsadress"
    },
    {
      "code" : "physical",
      "display" : "fysisk adress"
    },
    {
      "code" : "both",
      "display" : "utdelningsadress och fysisk adress"
    }
  ]
}

```
