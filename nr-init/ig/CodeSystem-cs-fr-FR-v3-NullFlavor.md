# NullFlavor - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **NullFlavor**

## CodeSystem: NullFlavor 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-NullFlavor | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:NullFlavor |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
A collection of codes specifying why a valid value is not present. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-NullFlavor",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-NullFlavor",
  "version" : "0.1.0",
  "name" : "NullFlavor",
  "title" : "NullFlavor",
  "status" : "active",
  "date" : "2025-12-22T14:22:23+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "A collection of codes specifying why a valid value is not present.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-NullFlavor|3.0.0",
  "concept" : [
    {
      "code" : "NI",
      "display" : "ingen information"
    },
    {
      "code" : "NP",
      "display" : "saknas"
    },
    {
      "code" : "NAV",
      "display" : "tillfälligt otillgänligt"
    },
    {
      "code" : "DER",
      "display" : "härlett"
    },
    {
      "code" : "OTH",
      "display" : "annat"
    },
    {
      "code" : "UNC",
      "display" : "okodat"
    },
    {
      "code" : "INV",
      "display" : "ogiltigt"
    },
    {
      "code" : "MSK",
      "display" : "dolt"
    },
    {
      "code" : "NA",
      "display" : "ej tillämpligt"
    },
    {
      "code" : "UNK",
      "display" : "okänt"
    },
    {
      "code" : "NINF",
      "display" : "negativt oändligt"
    },
    {
      "code" : "PINF",
      "display" : "positivt oändligt"
    },
    {
      "code" : "ASKU",
      "display" : "efterfrågat men okänt"
    },
    {
      "code" : "NASK",
      "display" : "ej efterfrågat"
    },
    {
      "code" : "NAVU",
      "display" : "ej tillgängligt"
    },
    {
      "code" : "QS",
      "display" : "tillräcklig mängd"
    },
    {
      "code" : "TRC",
      "display" : "endast spår"
    }
  ]
}

```
