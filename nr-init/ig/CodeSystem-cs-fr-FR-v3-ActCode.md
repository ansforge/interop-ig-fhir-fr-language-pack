# ActCode - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ActCode**

## CodeSystem: ActCode 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ActCode | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ActCode |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
A code specifying the particular kind of Act that the Act-instance represents within its class. 
**Constraints:**The kind of Act (e.g. physical examination, serum potassium, inpatient encounter, charge financial transaction, etc.) is specified with a code from one of several, typically external, coding systems. The coding system will depend on the class of Act, such as LOINC for observations, etc. 
Conceptually, the Act.code must be a specialization of the Act.classCode. This is why the structure of ActClass domain should be reflected in the superstructure of the ActCode domain and then individual codes or externally referenced vocabularies subordinated under these domains that reflect the ActClass structure. 
Act.classCode and Act.code are not modifiers of each other but the Act.code concept should really imply the Act.classCode concept. For a negative example, it is not appropriate to use an Act.code "potassium" together with and Act.classCode for "laboratory observation" to somehow mean "potassium laboratory observation" and then use the same Act.code for "potassium" together with Act.classCode for "medication" to mean "substitution of potassium". This mutually modifying use of Act.code and Act.classCode is not permitted. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-ActCode",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ActCode",
  "version" : "0.1.0",
  "name" : "ActCode",
  "title" : "ActCode",
  "status" : "active",
  "date" : "2025-12-22T17:37:51+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "A code specifying the particular kind of Act that the Act-instance represents within its class.\r\n\r\n*Constraints:* The kind of Act (e.g. physical examination, serum potassium, inpatient encounter, charge financial transaction, etc.) is specified with a code from one of several, typically external, coding systems. The coding system will depend on the class of Act, such as LOINC for observations, etc.\r\n\r\nConceptually, the Act.code must be a specialization of the Act.classCode. This is why the structure of ActClass domain should be reflected in the superstructure of the ActCode domain and then individual codes or externally referenced vocabularies subordinated under these domains that reflect the ActClass structure.\r\n\r\nAct.classCode and Act.code are not modifiers of each other but the Act.code concept should really imply the Act.classCode concept. For a negative example, it is not appropriate to use an Act.code \"potassium\" together with and Act.classCode for \"laboratory observation\" to somehow mean \"potassium laboratory observation\" and then use the same Act.code for \"potassium\" together with Act.classCode for \"medication\" to mean \"substitution of potassium\". This mutually modifying use of Act.code and Act.classCode is not permitted.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-ActCode|9.0.0",
  "concept" : [
    {
      "code" : "AMB",
      "display" : "Ambulatoire (hors établissement)"
    },
    {
      "code" : "EMER",
      "display" : "Passage aux urgences (établissement)"
    },
    {
      "code" : "FLD",
      "display" : "Terrain (voie publique, hélicoptère, ambulance, etc.)"
    },
    {
      "code" : "HH",
      "display" : "Soins à domicile (hors établissement)"
    },
    {
      "code" : "IMP",
      "display" : "Hospitalisation (établissement, y compris HAD)"
    },
    {
      "code" : "OBSENC",
      "display" : "Observation"
    },
    {
      "code" : "PRENC",
      "display" : "Pré-admission"
    },
    {
      "code" : "SS",
      "display" : "Hospitalisation de jour"
    },
    {
      "code" : "VR",
      "display" : "Virtuelle (exemple : RCP en l'absence du patient)"
    },
    {
      "code" : "CIRCLE",
      "display" : "Cercle"
    },
    {
      "code" : "ELLIPSE",
      "display" : "Elipse"
    },
    {
      "code" : "POINT",
      "display" : "Point"
    },
    {
      "code" : "POLY",
      "display" : "Multi"
    },
    {
      "code" : "DRUG",
      "display" : "Médicament"
    },
    {
      "code" : "FD",
      "display" : "Aliment"
    },
    {
      "code" : "BOOSTER",
      "display" : "Rappel de vaccin"
    },
    {
      "code" : "IMMUNIZ",
      "display" : "Vaccination sans autre précision"
    },
    {
      "code" : "INITIMMUNIZ",
      "display" : "1ère série vaccinante"
    },
    {
      "code" : "SEV",
      "display" : "Sévérité"
    },
    {
      "code" : "FFC",
      "display" : "Première dispensation - complète"
    },
    {
      "code" : "FFP",
      "display" : "Première dispensation - partielle"
    },
    {
      "code" : "RFP",
      "display" : "Dispensation suivante - partielle"
    },
    {
      "code" : "RFC",
      "display" : "Dispensation suivante - complète"
    }
  ]
}

```
