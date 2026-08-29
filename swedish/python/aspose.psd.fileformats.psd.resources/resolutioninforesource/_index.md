---
title: "ResolutionInfoResource klass"
type: docs
weight: 230
url: /sv/python-net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Summary:** The resolution info resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ResolutionInfoResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ResolutionInfoResource()](#ResolutionInfoResource__1) | Initierar en ny instans av ResolutionInfoResource klass |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Resurssignaturen för ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Den vanliga Photoshop-resurssignaturen. |
| data_size | int | r | Hämtar resursens datastorlek i byte. |
| h_dpi | [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal) | r/w | Horisontell DPI. |
| h_res_display_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit/) | r/w | Visningsenheter för horisontell upplösning.  Detta påverkar endast<br/>            användargränssnittet; upplösningen lagras fortfarande i PSD-filen<br/>            som pixlar/tum. |
| height_display_unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | Hämtar eller anger enheten för höjddisplayen. |
| id | short | r/w | Hämtar eller anger den unika identifieraren för resursen. |
| minimal_version | int | r | Hämtar den minsta erforderliga PSD-versionen. |
| name | string | r/w | Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0). |
| signatur | int | r | Hämtar resursens signatur. Ska alltid vara '8BIM'. |
| storlek | int | r | Hämtar resursblockets storlek i byte inklusive dess data. |
| v_dpi | [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal) | r/w | Vertikal DPI. |
| v_res_display_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit/) | r/w | Displayenheter för vertikal upplösning. |
| width_display_unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | Hämtar eller anger enheten för bredddisplayen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream)](#save_stream_1) | Sparar resursblocket till den angivna strömmen. |
| validate_values() | Validerar resursvärdena. |


### Constructor: ResolutionInfoResource() {#ResolutionInfoResource__1}


```
 ResolutionInfoResource() 
```

Initierar en ny instans av ResolutionInfoResource klass

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Sparar resursblocket till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömmen att spara resursblocket till. |

