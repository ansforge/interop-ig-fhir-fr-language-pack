# MediaType - French language pack for FHIR R4 v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **MediaType**

## CodeSystem: MediaType 

| | |
| :--- | :--- |
| **:https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-mediaType | **:0.1.0 |
| Active | **:MediaType |
| **: This material derives from the HL7 Terminology THO. THO is copyright ©1989+ Health Level Seven International and is made available under the CC0 designation. For more licensing information see: https://terminology.hl7.org/license.html | |

 
Internet Assigned Numbers Authority (IANA) Mime Media Types. Identifies the type of the encapsulated data and identifies a method to interpret or render the data. The IANA defined domain of media types is established by the Internet standard RFC 2045 [http://www.ietf.org/rfc/rfc2045.txt] and 2046 [http://www.ietf.org/rfc/rfc2046.txt]. RFC 2046 defines the media type to consist of two parts: 
1. top level media type, and
1. media subtype
 
However, this HL7 datatypes specification treats the entire media type as one atomic code symbol in the form defined by IANA, i.e., top level type followed by a slash "/" followed by media subtype. Currently defined media types are registered in a database [http://www.iana.org/assignments/media-types/index.html] maintained by IANA. Currently several hundred different MIME media types are defined, with the list growing rapidly. In general, all those types defined by the IANA MAY be used. 

* Ce supplément de terminologie de référence (CodeSystem) nest pas utilisé ici; il peut être utilisé ailleurs (par exemple spécifications et/ou implémentations qui utilisent ce contenu)

-------

 . 



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "cs-fr-FR-v3-mediaType",
  "language" : "fr-FR",
  "url" : "https://interop.esante.gouv.fr/ig/fhir/fr/CodeSystem/cs-fr-FR-v3-mediaType",
  "version" : "0.1.0",
  "name" : "MediaType",
  "title" : "Media Type",
  "status" : "active",
  "date" : "2025-12-23T09:21:12+00:00",
  "publisher" : "Agence du Numérique en Santé (ANS) - 2-10 Rue d'Oradour-sur-Glane, 75015 Paris",
  "description" : "Internet Assigned Numbers Authority (IANA) Mime Media Types. Identifies the type of the encapsulated data and identifies a method to interpret or render the data. The IANA defined domain of media types is established by the Internet standard RFC 2045 \\[http://www.ietf.org/rfc/rfc2045.txt\\] and 2046 \\[http://www.ietf.org/rfc/rfc2046.txt\\]. RFC 2046 defines the media type to consist of two parts:\r\n\r\n1.  top level media type, and\r\n2.  media subtype\r\n\r\nHowever, this HL7 datatypes specification treats the entire media type as one atomic code symbol in the form defined by IANA, i.e., top level type followed by a slash \"/\" followed by media subtype. Currently defined media types are registered in a database \\[http://www.iana.org/assignments/media-types/index.html\\] maintained by IANA. Currently several hundred different MIME media types are defined, with the list growing rapidly. In general, all those types defined by the IANA MAY be used.",
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
  "supplements" : "http://terminology.hl7.org/CodeSystem/v3-mediaType|3.0.0",
  "concept" : [
    {
      "code" : "application/dicom",
      "display" : "DICOM"
    },
    {
      "code" : "application/msword",
      "display" : "MSWORD"
    },
    {
      "code" : "application/pdf",
      "display" : "PDF"
    },
    {
      "code" : "audio/basic",
      "display" : "Basic Audio"
    },
    {
      "code" : "audio/k32adpcm",
      "display" : "K32ADPCM Audio"
    },
    {
      "code" : "audio/mpeg",
      "display" : "MPEG audio layer 3 MP3 Audio"
    },
    {
      "code" : "image/gif",
      "display" : "GIF Image"
    },
    {
      "code" : "image/jpeg",
      "display" : "JPEG Image"
    },
    {
      "code" : "image/png",
      "display" : "PNG Image"
    },
    {
      "code" : "image/tiff",
      "display" : "TIFF Image"
    },
    {
      "code" : "text/html",
      "display" : "HTML Text"
    },
    {
      "code" : "text/plain",
      "display" : "Plain Text"
    },
    {
      "code" : "text/rtf",
      "display" : "RTF Text"
    },
    {
      "code" : "text/xml",
      "display" : "XML Text"
    }
  ]
}

```
