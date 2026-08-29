---
title: "WorkingPathResource-klass"
type: docs
weight: 320
url: /sv/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Summary:** Working path resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.WorkingPathResource

**Inheritance:** IVectorPathData, ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [WorkingPathResource(data_bytes)](#WorkingPathResource_data_bytes_1) | Initierar en ny instans av klassen [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Resurssignaturen för ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Den vanliga Photoshop-resurssignaturen. |
| data_size | int | r | Hämtar resursens datastorlek i byte. |
| id | short | r/w | Hämtar eller anger den unika identifieraren för resursen. |
| is_disabled | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är inaktiverad. |
| is_inverted | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är inverterad. |
| is_not_linked | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans inte är länkad. |
| minimal_version | int | r | Hämtar den minsta erforderliga PSD-versionen. |
| name | string | r/w | Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0). |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Hämtar eller anger sökvägsposterna. |
| signatur | int | r | Hämtar resursens signatur. Ska alltid vara '8BIM'. |
| storlek | int | r | Hämtar resursblockets storlek i byte inklusive dess data. |
| version | int | r/w | Hämtar eller anger versionen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream)](#save_stream_1) | Sparar resursblocket till den angivna strömmen. |
| validate_values() | Validerar resursvärdena. |


### Constructor: WorkingPathResource(data_bytes) {#WorkingPathResource_data_bytes_1}


```
 WorkingPathResource(data_bytes) 
```

Initierar en ny instans av klassen [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data_bytes | byte | Data för vektorvägen. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Sparar resursblocket till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömmen att spara resursblocket till. |

