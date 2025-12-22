# RoleClass - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **RoleClass**

## CodeSystem: RoleClass 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-RoleClass | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:RoleClass |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
Codes for the Role class hierarchy. The values in this hierarchy, represent a Role which is an association or relationship between two entities - the entity that plays the role and the entity that scopes the role. Roles names are derived from the name of the playing entity in that role. 
The role hierarchy stems from three core concepts, or abstract domains: 
* **RoleClassOntological** is an abstract domain that collects roles in which the playing entity is defined or specified by the scoping entity.
* **RoleClassPartitive** collects roles in which the playing entity is in some sense a "part" of the scoping entity.
* **RoleClassAssociative** collects all of the remaining forms of association between the playing entity and the scoping entity. This set of roles is further partitioned between:
 
The hierarchy discussed above is represented In the current vocabulary tables as a set of abstract domains, with the exception of the "Personal relationship" which is a leaf concept. 
**OpenIssue:**Description copied from Concept Domain of same name. Must be verified. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-RoleClass",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-RoleClass",
  "version" : "0.1.0",
  "name" : "RoleClass",
  "title" : "RoleClass",
  "status" : "active",
  "date" : "2025-12-22T17:10:15+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "Codes for the Role class hierarchy. The values in this hierarchy, represent a Role which is an association or relationship between two entities - the entity that plays the role and the entity that scopes the role. Roles names are derived from the name of the playing entity in that role.\r\n\r\nThe role hierarchy stems from three core concepts, or abstract domains:\r\n\r\n *  **RoleClassOntological** is an abstract domain that collects roles in which the playing entity is defined or specified by the scoping entity.\r\n *  **RoleClassPartitive** collects roles in which the playing entity is in some sense a \"part\" of the scoping entity.\r\n *  **RoleClassAssociative** collects all of the remaining forms of association between the playing entity and the scoping entity. This set of roles is further partitioned between:\r\n    \r\n     *  **RoleClassPassive** which are roles in which the playing entity is used, known, treated, handled, built, or destroyed, etc. under the auspices of the scoping entity. The playing entity is passive in these roles in that the role exists without an agreement from the playing entity.\r\n     *  **RoleClassMutualRelationship** which are relationships based on mutual behavior of the two entities. The basis of these relationship may be formal agreements or they may be *de facto* behavior. Thus, this sub-domain is further divided into:\r\n        \r\n         *  **RoleClassRelationshipFormal** in which the relationship is formally defined, frequently by a contract or agreement.\r\n         *  **Personal relationship** which inks two people in a personal relationship.\r\n\r\nThe hierarchy discussed above is represented In the current vocabulary tables as a set of abstract domains, with the exception of the \"Personal relationship\" which is a leaf concept.\r\n\r\n*OpenIssue:* Description copied from Concept Domain of same name. Must be verified.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-RoleClass|4.0.0",
  "concept" : [
    {
      "code" : "INGR",
      "display" : "Ingrédient"
    },
    {
      "code" : "ACTI",
      "display" : "Ingredient actif"
    },
    {
      "code" : "ADJV",
      "display" : "Adjuvant"
    },
    {
      "code" : "ADTV",
      "display" : "Additif"
    },
    {
      "code" : "BASE",
      "display" : "Base"
    },
    {
      "code" : "CNTM",
      "display" : "Ingredient contaminant"
    },
    {
      "code" : "IACT",
      "display" : "Ingredient inactif"
    },
    {
      "code" : "MECH",
      "display" : "Ingrédient mécanique"
    }
  ]
}

```
