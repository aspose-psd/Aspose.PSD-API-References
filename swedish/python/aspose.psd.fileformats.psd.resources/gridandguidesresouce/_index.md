---
title: "GridAndGuidesResouce-klass"
type: docs
weight: 110
url: /sv/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | Initierar en ny instans av klassen GridAndGuidesResouce |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Resurssignaturen för ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Den vanliga Photoshop-resurssignaturen. |
| data_size | int | r | Hämtar resursens datastorlek i byte. |
| grid_cycle_x | int | r/w | Hämtar eller anger den horisontella rutnätscykeln. Standardvärdet är 576. |
| grid_cycle_y | int | r/w | Hämtar eller anger den vertikala rutnätscykeln. Standardvärdet är 576. |
| guide_count | int | r | Hämtar antalet guide-resursblock. |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | Hämtar eller anger guiderna. |
| header_version | int | r/w | Hämtar eller anger header version. Detta värde ska alltid vara 1. |
| id | short | r/w | Hämtar eller anger den unika identifieraren för resursen. |
| minimal_version | int | r | Hämtar den minsta erforderliga PSD-versionen. |
| name | string | r/w | Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0). |
| signatur | int | r | Hämtar resursens signatur. Ska alltid vara '8BIM'. |
| storlek | int | r | Hämtar resursblockets storlek i byte inklusive dess data. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream)](#save_stream_1) | Sparar resursblocket till den angivna strömmen. |
| validate_values() | Validerar resursvärdena. |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

Initierar en ny instans av klassen GridAndGuidesResouce

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Sparar resursblocket till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömmen att spara resursblocket till. |

