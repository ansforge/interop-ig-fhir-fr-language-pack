# ParticipationType - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ParticipationType**

## CodeSystem: ParticipationType 

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ParticipationType | *Version*:0.1.0 |
| Active as of 2025-12-22 | *Computable Name*:ParticipationType |
| **Copyright/Legal**: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
A code specifying the meaning and purpose of every Participation instance. Each of its values implies specific constraints on the Roles undertaking the participation. 

 Cette terminologie de référence (CodeSystem) est référencé dans la définition de contenu des jeux de valeurs (ValueSet) suivants : 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-ParticipationType",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-ParticipationType",
  "version" : "0.1.0",
  "name" : "ParticipationType",
  "title" : "ParticipationType",
  "status" : "active",
  "date" : "2025-12-22T17:21:11+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "A code specifying the meaning and purpose of every Participation instance. Each of its values implies specific constraints on the Roles undertaking the participation.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-ParticipationType|5.0.0",
  "concept" : [
    {
      "code" : "ADM",
      "display" : "Responsable de l'admission"
    },
    {
      "code" : "ALY",
      "display" : "Cible d'une observation (substance ou composant le plus spécifique)"
    },
    {
      "code" : "ATND",
      "display" : "Superviseur / Responsable des soins"
    },
    {
      "code" : "AUT",
      "display" : "Auteur"
    },
    {
      "code" : "AUTHEN",
      "display" : "Valideur des résultats (ex : un biologiste ou un système expert)"
    },
    {
      "code" : "BBY",
      "display" : "Nouveau né"
    },
    {
      "code" : "BEN",
      "display" : "Bénéficiaire"
    },
    {
      "code" : "CAGNT",
      "display" : "Agent causal"
    },
    {
      "code" : "CALLBCK",
      "display" : "Contact à rappeler"
    },
    {
      "code" : "CAT",
      "display" : "Catalyseur"
    },
    {
      "code" : "CON",
      "display" : "Consultant"
    },
    {
      "code" : "COV",
      "display" : "Partie couverte (titulaire ou bénéficiaire)"
    },
    {
      "code" : "CSM",
      "display" : "Consommable"
    },
    {
      "code" : "CST",
      "display" : "Responsable de l'information"
    },
    {
      "code" : "DEV",
      "display" : "Dispositif automatique impliqué dans la production des résultats"
    },
    {
      "code" : "DIR",
      "display" : "Participant direct"
    },
    {
      "code" : "DIS",
      "display" : "Responsable de la sortie"
    },
    {
      "code" : "DIST",
      "display" : "Distributeur"
    },
    {
      "code" : "DON",
      "display" : "Donneur"
    },
    {
      "code" : "DST",
      "display" : "Destination"
    },
    {
      "code" : "ELOC",
      "display" : "Emplacement où les données sont saisies"
    },
    {
      "code" : "ENT",
      "display" : "Transcripteur du contenu à partir d'une autre forme"
    },
    {
      "code" : "ESC",
      "display" : "Accompagnateur"
    },
    {
      "code" : "EXPAGNT",
      "display" : "Agent de l'exposition"
    },
    {
      "code" : "EXPART",
      "display" : "Partie de l'exposition"
    },
    {
      "code" : "EXSRC",
      "display" : "Source de l'exposition"
    },
    {
      "code" : "EXPTRGT",
      "display" : "Cible de l'exposition"
    },
    {
      "code" : "GUAR",
      "display" : "Garant"
    },
    {
      "code" : "HLD",
      "display" : "Souscripteur"
    },
    {
      "code" : "IND",
      "display" : "Cible indirecte"
    },
    {
      "code" : "INF",
      "display" : "Informateur"
    },
    {
      "code" : "IRCP",
      "display" : "Destinataire de l'information"
    },
    {
      "code" : "LA",
      "display" : "Responsable légal de l'acte"
    },
    {
      "code" : "LOC",
      "display" : "Emplacement principal"
    },
    {
      "code" : "NRD",
      "display" : "Dispositif non réutilisable"
    },
    {
      "code" : "NOT",
      "display" : "Personne à prévenir en cas d'urgence"
    },
    {
      "code" : "ORG",
      "display" : "Lieu d'origine"
    },
    {
      "code" : "PART",
      "display" : "Participant"
    },
    {
      "code" : "PPRF",
      "display" : "Exécutant principal"
    },
    {
      "code" : "PRCP",
      "display" : "Destinataire principal de l'information"
    },
    {
      "code" : "PRD",
      "display" : "Produit"
    },
    {
      "code" : "PRF",
      "display" : "Exécutant"
    },
    {
      "code" : "RCT",
      "display" : "Dossier médical"
    },
    {
      "code" : "RCV",
      "display" : "Récepteur"
    },
    {
      "code" : "RDV",
      "display" : "Dispositif réutilisable"
    },
    {
      "code" : "REF",
      "display" : "Référent / Prescripteur"
    },
    {
      "code" : "REFB",
      "display" : "Personne ayant adressé le patient"
    },
    {
      "code" : "REFT",
      "display" : "Personne recevant le patient"
    },
    {
      "code" : "RESP",
      "display" : "Responsable de l'acte"
    },
    {
      "code" : "RML",
      "display" : "Emplacement distant"
    },
    {
      "code" : "SBJ",
      "display" : "Sujet"
    },
    {
      "code" : "SPC",
      "display" : "Echantillon"
    },
    {
      "code" : "SPRF",
      "display" : "Exécutant secondaire"
    },
    {
      "code" : "TRANS",
      "display" : "Transcripteur"
    },
    {
      "code" : "TRC",
      "display" : "Personne recevant une copie de l'information"
    },
    {
      "code" : "VIA",
      "display" : "Emplacement intermédiaire"
    },
    {
      "code" : "VRF",
      "display" : "Vérificateur"
    },
    {
      "code" : "WIT",
      "display" : "Témoin"
    }
  ]
}

```
