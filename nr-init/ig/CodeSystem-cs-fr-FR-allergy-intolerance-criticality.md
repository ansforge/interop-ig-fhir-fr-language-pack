# AllergyIntoleranceCriticality - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **AllergyIntoleranceCriticality**

## CodeSystem: AllergyIntoleranceCriticality 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-allergy-intolerance-criticality | *Version*:0.1.0 |
| Draft as of 2025-12-23 | *Computable Name*:AllergyIntoleranceCriticality |

 
Estimate of the potential clinical harm, or seriousness, of a reaction to an identified substance. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-allergy-intolerance-criticality",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-allergy-intolerance-criticality",
  "version" : "0.1.0",
  "name" : "AllergyIntoleranceCriticality",
  "title" : "AllergyIntoleranceCriticality",
  "status" : "draft",
  "date" : "2025-12-23T08:56:57+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "Estimate of the potential clinical harm, or seriousness, of a reaction to an identified substance.",
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
  "supplements" : "http://hl7.org/fhir/allergy-intolerance-criticality|4.0.1",
  "concept" : [
    {
      "code" : "low",
      "display" : "Bas"
    },
    {
      "code" : "high",
      "display" : "Elevé"
    },
    {
      "code" : "unable-to-assess",
      "display" : "Impossible à évaluer"
    }
  ]
}

```
