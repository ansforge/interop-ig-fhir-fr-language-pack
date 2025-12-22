# IdentifierType - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **IdentifierType**

## CodeSystem: IdentifierType 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v2-0203 | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:IdentifierType |
| **Copyright/Legal**: This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
HL7-defined code system of concepts specifying type of identifier. Used in HL7 Version 2.x messaging data types CX, PLN, PPN, XCN and XON. 

 
Underlying Master Code System for V2 table 0203 (Identifier Type) 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v2-0203",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v2-0203",
  "version" : "0.1.0",
  "name" : "IdentifierType",
  "title" : "identifierType",
  "status" : "active",
  "date" : "2025-12-22T14:22:23+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "HL7-defined code system of concepts specifying type of identifier. Used in HL7 Version 2.x messaging data types CX, PLN, PPN, XCN and XON.",
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
  "purpose" : "Underlying Master Code System for V2 table 0203 (Identifier Type)",
  "copyright" : "This material derives from the HL7 Terminology (THO). THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html",
  "caseSensitive" : false,
  "content" : "supplement",
  "supplements" : "http://terminology.hl7.org/CodeSystem/v2-0203|5.0.0",
  "concept" : [
    {
      "code" : "AC"
    },
    {
      "code" : "ACSN"
    },
    {
      "code" : "AIN"
    },
    {
      "code" : "AM"
    },
    {
      "code" : "AMA"
    },
    {
      "code" : "AN"
    },
    {
      "code" : "ANC"
    },
    {
      "code" : "AND"
    },
    {
      "code" : "ANON"
    },
    {
      "code" : "ANT"
    },
    {
      "code" : "APRN"
    },
    {
      "code" : "ASID"
    },
    {
      "code" : "BA"
    },
    {
      "code" : "BC"
    },
    {
      "code" : "BCFN"
    },
    {
      "code" : "BCT"
    },
    {
      "code" : "BR"
    },
    {
      "code" : "BRN"
    },
    {
      "code" : "BSNR"
    },
    {
      "code" : "CAAI"
    },
    {
      "code" : "CC"
    },
    {
      "code" : "CONM"
    },
    {
      "code" : "CY"
    },
    {
      "code" : "CZ"
    },
    {
      "code" : "DC"
    },
    {
      "code" : "DCFN"
    },
    {
      "code" : "DDS"
    },
    {
      "code" : "DEA"
    },
    {
      "code" : "DFN"
    },
    {
      "code" : "DI"
    },
    {
      "code" : "DL"
    },
    {
      "code" : "DN"
    },
    {
      "code" : "DO"
    },
    {
      "code" : "DP"
    },
    {
      "code" : "DPM"
    },
    {
      "code" : "DR"
    },
    {
      "code" : "DS"
    },
    {
      "code" : "DSG"
    },
    {
      "code" : "EI"
    },
    {
      "code" : "EN"
    },
    {
      "code" : "ESN"
    },
    {
      "code" : "FDR"
    },
    {
      "code" : "FDRFN"
    },
    {
      "code" : "FGN"
    },
    {
      "code" : "FI"
    },
    {
      "code" : "FILL"
    },
    {
      "code" : "GI"
    },
    {
      "code" : "GIN"
    },
    {
      "code" : "GL"
    },
    {
      "code" : "GN"
    },
    {
      "code" : "HC"
    },
    {
      "code" : "IND"
    },
    {
      "code" : "IRISTEM"
    },
    {
      "code" : "JHN"
    },
    {
      "code" : "LACSN"
    },
    {
      "code" : "LANR"
    },
    {
      "code" : "LI"
    },
    {
      "code" : "L&I"
    },
    {
      "code" : "LN"
    },
    {
      "code" : "LR"
    },
    {
      "code" : "MA"
    },
    {
      "code" : "MB"
    },
    {
      "code" : "MC"
    },
    {
      "code" : "MCD"
    },
    {
      "code" : "MCN"
    },
    {
      "code" : "MCR"
    },
    {
      "code" : "MCT"
    },
    {
      "code" : "MD"
    },
    {
      "code" : "MI"
    },
    {
      "code" : "MR"
    },
    {
      "code" : "MRT"
    },
    {
      "code" : "MS"
    },
    {
      "code" : "NBSNR"
    },
    {
      "code" : "NCT"
    },
    {
      "code" : "NE"
    },
    {
      "code" : "NH"
    },
    {
      "code" : "NI"
    },
    {
      "code" : "NII"
    },
    {
      "code" : "NIIP"
    },
    {
      "code" : "NNxxx"
    },
    {
      "code" : "NP"
    },
    {
      "code" : "NPI"
    },
    {
      "code" : "OBI"
    },
    {
      "code" : "OD"
    },
    {
      "code" : "PA"
    },
    {
      "code" : "PC"
    },
    {
      "code" : "PCN"
    },
    {
      "code" : "PE"
    },
    {
      "code" : "PEN"
    },
    {
      "code" : "PGN"
    },
    {
      "code" : "PHC"
    },
    {
      "code" : "PHE"
    },
    {
      "code" : "PHO"
    },
    {
      "code" : "PI"
    },
    {
      "code" : "PIN"
    },
    {
      "code" : "PLAC"
    },
    {
      "code" : "PN"
    },
    {
      "code" : "PNT"
    },
    {
      "code" : "PPIN"
    },
    {
      "code" : "PPN"
    },
    {
      "code" : "PRC"
    },
    {
      "code" : "PRN",
      "display" : "identifierare för vårdgivare eller utförare av socialtjänst"
    },
    {
      "code" : "PT"
    },
    {
      "code" : "QA"
    },
    {
      "code" : "RI"
    },
    {
      "code" : "RN"
    },
    {
      "code" : "RPH"
    },
    {
      "code" : "RR"
    },
    {
      "code" : "RRI"
    },
    {
      "code" : "RRP"
    },
    {
      "code" : "SAMN"
    },
    {
      "code" : "SB"
    },
    {
      "code" : "SID"
    },
    {
      "code" : "SL"
    },
    {
      "code" : "SN"
    },
    {
      "code" : "SNBSN"
    },
    {
      "code" : "SNO"
    },
    {
      "code" : "SP"
    },
    {
      "code" : "SR"
    },
    {
      "code" : "SRX"
    },
    {
      "code" : "SS"
    },
    {
      "code" : "STN"
    },
    {
      "code" : "TAX"
    },
    {
      "code" : "TN"
    },
    {
      "code" : "TPR"
    },
    {
      "code" : "TRL"
    },
    {
      "code" : "U"
    },
    {
      "code" : "UDI"
    },
    {
      "code" : "UPIN"
    },
    {
      "code" : "USID"
    },
    {
      "code" : "VN"
    },
    {
      "code" : "VP"
    },
    {
      "code" : "VS"
    },
    {
      "code" : "WC"
    },
    {
      "code" : "WCN"
    },
    {
      "code" : "WP"
    },
    {
      "code" : "XV"
    },
    {
      "code" : "XX",
      "display" : "identifierare för organisation"
    }
  ]
}

```
