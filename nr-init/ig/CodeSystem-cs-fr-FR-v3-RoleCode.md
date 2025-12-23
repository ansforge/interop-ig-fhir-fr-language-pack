# RoleCode - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **RoleCode**

## CodeSystem: RoleCode 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-RoleCode | *Version*:0.1.0 |
| Active as of 2025-12-23 | *Computable Name*:RoleCode |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
A set of codes further specifying the kind of Role; specific classification codes for further qualifying RoleClass codes. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-RoleCode",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-RoleCode",
  "version" : "0.1.0",
  "name" : "RoleCode",
  "title" : "RoleCode",
  "status" : "active",
  "date" : "2025-12-23T08:56:57+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "A set of codes further specifying the kind of Role; specific classification codes for further qualifying RoleClass codes.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-RoleCode|3.0.0",
  "concept" : [
    {
      "code" : "C",
      "display" : "Spécimen utilisé pour les paramètres d'étalonnage initiaux d'un instrument"
    },
    {
      "code" : "G",
      "display" : "Ensemble d'échantillons de patients dans lequel les individus du groupe peuvent ou non être identifiés."
    },
    {
      "code" : "L",
      "display" : "Aliquot d'échantillons individuels combinés pour former un seul spécimen représentant tous les individus inclus."
    },
    {
      "code" : "P",
      "display" : "Spécimen prélevé sur un patient"
    },
    {
      "code" : "ADOPTF",
      "display" : "Père adoptif"
    },
    {
      "code" : "ADOPTM",
      "display" : "Mère adoptive"
    },
    {
      "code" : "ADOPTP",
      "display" : "Parent adoptif, au sens père ou mère"
    },
    {
      "code" : "AUNT",
      "display" : "Tante"
    },
    {
      "code" : "BRO",
      "display" : "Frère"
    },
    {
      "code" : "BROINLAW",
      "display" : "Beau-frère"
    },
    {
      "code" : "CHILD",
      "display" : "Enfant"
    },
    {
      "code" : "CHLDADOPT",
      "display" : "Enfant adopté"
    },
    {
      "code" : "CHLDFOST",
      "display" : "Enfant placé en famille d'accueil"
    },
    {
      "code" : "CHLDINLAW",
      "display" : "Gendre ou belle-fille"
    },
    {
      "code" : "COUSN",
      "display" : "Cousin(e)"
    },
    {
      "code" : "DAU",
      "display" : "Fille biologique"
    },
    {
      "code" : "DAUADOPT",
      "display" : "Fille adoptive"
    },
    {
      "code" : "DAUC",
      "display" : "Fille"
    },
    {
      "code" : "DAUFOST",
      "display" : "Fille placée en famille d'accueil"
    },
    {
      "code" : "DAUINLAW",
      "display" : "Belle-fille"
    },
    {
      "code" : "DOMPART",
      "display" : "Concubin(e) ou partenaire PACS"
    },
    {
      "code" : "EXT",
      "display" : "Autre membre de la famille sans lien génétique direct"
    },
    {
      "code" : "FAMMEMB",
      "display" : "Autre membre de la famille"
    },
    {
      "code" : "FMRSPS",
      "display" : "Ancien époux ou ancienne épouse"
    },
    {
      "code" : "FRND",
      "display" : "Autre proche"
    },
    {
      "code" : "FTH",
      "display" : "Père"
    },
    {
      "code" : "FTHFOST",
      "display" : "Assistant familial - Famille d'accueil"
    },
    {
      "code" : "FTHINLAW",
      "display" : "Beau-père"
    },
    {
      "code" : "FTWIN",
      "display" : "Jumeau ou jumelle dizygote"
    },
    {
      "code" : "FTWINBRO",
      "display" : "Jumeau dizygote"
    },
    {
      "code" : "FTWINSIS",
      "display" : "Jumelle dizygote"
    },
    {
      "code" : "GESTM",
      "display" : "Mère porteuse"
    },
    {
      "code" : "GGRFTH",
      "display" : "Arrière-grand-père"
    },
    {
      "code" : "GGRMTH",
      "display" : "Arrière-grand-mère"
    },
    {
      "code" : "GGRPRN",
      "display" : "Arrière-grand-parent"
    },
    {
      "code" : "GRFTH",
      "display" : "Grand-père"
    },
    {
      "code" : "GRMTH",
      "display" : "Grand-mère"
    },
    {
      "code" : "GRPRN",
      "display" : "Grand-parent"
    },
    {
      "code" : "GRNDCHILD",
      "display" : "Petit-enfant"
    },
    {
      "code" : "GRNDDAU",
      "display" : "Petite-fille"
    },
    {
      "code" : "GRNDSON",
      "display" : "Petit-fils"
    },
    {
      "code" : "HBRO",
      "display" : "Demi-frère"
    },
    {
      "code" : "HSIB",
      "display" : "Demi-frère ou demi-sœur"
    },
    {
      "code" : "HSIS",
      "display" : "Demi-sœur"
    },
    {
      "code" : "HUSB",
      "display" : "Epoux"
    },
    {
      "code" : "ITWIN",
      "display" : "Jumeau ou jumelle monozygote"
    },
    {
      "code" : "ITWINBRO",
      "display" : "Jumeau monozygote"
    },
    {
      "code" : "ITWINSIS",
      "display" : "Jumelle monozygote"
    },
    {
      "code" : "MAUNT",
      "display" : "Tante maternelle"
    },
    {
      "code" : "MCOUSN",
      "display" : "Cousin (maternel)"
    },
    {
      "code" : "MGGRFTH",
      "display" : "Arrière-grand-père maternel"
    },
    {
      "code" : "MGGRMTH",
      "display" : "Arrière-grand-mère maternelle"
    },
    {
      "code" : "MGGRPRN",
      "display" : "Arrière grand parent maternel"
    },
    {
      "code" : "MGRFTH",
      "display" : "Grand-père maternel"
    },
    {
      "code" : "MGRMTH",
      "display" : "Grand-mère maternelle"
    },
    {
      "code" : "MGRPRN",
      "display" : "Grand parent maternel"
    },
    {
      "code" : "MTH",
      "display" : "Mère"
    },
    {
      "code" : "MTHFOST",
      "display" : "Assistante familiale - Famille d'accueil"
    },
    {
      "code" : "MTHINLAW",
      "display" : "Belle-mère"
    },
    {
      "code" : "MUNCLE",
      "display" : "Oncle maternel"
    },
    {
      "code" : "NBOR",
      "display" : "Voisin(e)"
    },
    {
      "code" : "NBRO",
      "display" : "Frère biologique"
    },
    {
      "code" : "NCHILD",
      "display" : "Enfant biologique"
    },
    {
      "code" : "NEPHEW",
      "display" : "Neveu"
    },
    {
      "code" : "NFTH",
      "display" : "Père biologique"
    },
    {
      "code" : "NFTHF",
      "display" : "Père biologique du fœtus"
    },
    {
      "code" : "NIECE",
      "display" : "Nièce"
    },
    {
      "code" : "NIENEPH",
      "display" : "Neveu ou nièce"
    },
    {
      "code" : "NMTH",
      "display" : "Mère biologique"
    },
    {
      "code" : "NMTHF",
      "display" : "Mère biologique du fœtus"
    },
    {
      "code" : "NPRN",
      "display" : "Parent biologique, au sens père ou mère"
    },
    {
      "code" : "NSIB",
      "display" : "Frère ou soeur biologique"
    },
    {
      "code" : "NSIS",
      "display" : "Soeur biologique"
    },
    {
      "code" : "PAUNT",
      "display" : "Tante paternelle"
    },
    {
      "code" : "PCOUSN",
      "display" : "Cousin (paternel)"
    },
    {
      "code" : "PGGRFTH",
      "display" : "Arrière-grand-père paternel"
    },
    {
      "code" : "PGGRMTH",
      "display" : "Arrière-grand-mère paternelle"
    },
    {
      "code" : "PGGRPRN",
      "display" : "Arrière grand parent paternel"
    },
    {
      "code" : "PGRFTH",
      "display" : "Grand-père paternel"
    },
    {
      "code" : "PGRMTH",
      "display" : "Grand-mère paternelle"
    },
    {
      "code" : "PGRPRN",
      "display" : "Grand parent paternel"
    },
    {
      "code" : "PRN",
      "display" : "Parent, au sens père ou mère"
    },
    {
      "code" : "PRNINLAW",
      "display" : "Beau-père ou belle-mère"
    },
    {
      "code" : "PRNFOST",
      "display" : "Parent, au sens famille d'accueil"
    },
    {
      "code" : "PUNCLE",
      "display" : "Oncle paternel"
    },
    {
      "code" : "RESPRSN",
      "display" : "Responsable légal non membre de la famille"
    },
    {
      "code" : "ROOM",
      "display" : "Personne vivant sous le même toit"
    },
    {
      "code" : "SIB",
      "display" : "Frère ou sœur"
    },
    {
      "code" : "SIBINLAW",
      "display" : "Beau-frère ou belle-sœur"
    },
    {
      "code" : "SIGOTHR",
      "display" : "Conjoint"
    },
    {
      "code" : "SIS",
      "display" : "Sœur"
    },
    {
      "code" : "SISINLAW",
      "display" : "Belle-sœur"
    },
    {
      "code" : "SON",
      "display" : "Fils biologique"
    },
    {
      "code" : "SONADOPT",
      "display" : "Fils adoptif"
    },
    {
      "code" : "SONC",
      "display" : "Fils"
    },
    {
      "code" : "SONFOST",
      "display" : "Garçon placé en famille d'accueil"
    },
    {
      "code" : "SONINLAW",
      "display" : "Gendre"
    },
    {
      "code" : "SPS",
      "display" : "Epoux ou épouse"
    },
    {
      "code" : "STPBRO",
      "display" : "Fils du beau-père ou de la belle-mère"
    },
    {
      "code" : "STPFTH",
      "display" : "Beau-père - époux du père ou de la mère"
    },
    {
      "code" : "STPMTH",
      "display" : "Belle-mère - épouse du père ou de la mère"
    },
    {
      "code" : "STPCHLD",
      "display" : "Enfant du conjoint, issu d'un mariage précédent"
    },
    {
      "code" : "STPDAU",
      "display" : "Fille du conjoint, issue d'un mariage précédent"
    },
    {
      "code" : "STPPRN",
      "display" : "Beau-père ou belle-mère - époux(se) du père ou de la mère"
    },
    {
      "code" : "STPSIB",
      "display" : "Enfant du beau-père ou de la belle-mère"
    },
    {
      "code" : "STPSIS",
      "display" : "Fille du beau-père ou de la belle-mère"
    },
    {
      "code" : "STPSON",
      "display" : "Fils du conjoint, issu d'un mariage précédent"
    },
    {
      "code" : "TWIN",
      "display" : "Frère jumeau ou soeur jumelle"
    },
    {
      "code" : "TWINBRO",
      "display" : "Frère jumeau"
    },
    {
      "code" : "TWINSIS",
      "display" : "Soeur jumelle"
    },
    {
      "code" : "UNCLE",
      "display" : "Oncle"
    },
    {
      "code" : "WIFE",
      "display" : "Epouse"
    },
    {
      "code" : "FAMDEP",
      "display" : "Couverture familiale"
    },
    {
      "code" : "STUD",
      "display" : "Couverture étudiante"
    },
    {
      "code" : "SELF",
      "display" : "Couverture personnelle"
    }
  ]
}

```
