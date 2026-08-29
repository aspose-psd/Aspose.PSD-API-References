---
title: "TransparencyIndexResource-klass"
type: docs
weight: 260
url: /sv/python-net/aspose.psd.fileformats.psd.resources/transparencyindexresource/
---

**Summary:** The transparency index resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.TransparencyIndexResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [TransparencyIndexResource()](#TransparencyIndexResource__1) | Initierar en ny instans av klassen TransparencyIndexResource |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Resurssignaturen för ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Den vanliga Photoshop-resurssignaturen. |
| data_size | int | r | Hämtar resursens datastorlek i byte. |
| id | short | r/w | Hämtar eller anger den unika identifieraren för resursen. |
| minimal_version | int | r | Hämtar den minsta erforderliga PSD-versionen. |
| name | string | r/w | Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0). |
| signatur | int | r | Hämtar resursens signatur. Ska alltid vara '8BIM'. |
| storlek | int | r | Hämtar resursblockets storlek i byte inklusive dess data. |
| transparency_index | short | r/w | Hämtar eller anger transparensfärgindexet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream)](#save_stream_1) | Sparar resursblocket till den angivna strömmen. |
| validate_values() | Validerar resursvärdena. |


### Constructor: TransparencyIndexResource() {#TransparencyIndexResource__1}


```
 TransparencyIndexResource() 
```

Initierar en ny instans av klassen TransparencyIndexResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Sparar resursblocket till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömmen att spara resursblocket till. |

