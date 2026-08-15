---
title: "Thumbnail4Resource-klass"
type: docs
weight: 240
url: /sv/python-net/aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Summary:** Represents the thumbnail resource for psd 4.0.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.Thumbnail4Resource

**Inheritance:** ThumbnailResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Thumbnail4Resource()](#Thumbnail4Resource__1) | Initierar en ny instans av Thumbnail4Resource-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Resurssignaturen för ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Den vanliga Photoshop-resurssignaturen. |
| bits_pixel | short | r/w | Hämtar eller anger bits-pixelen. |
| data_size | int | r | Hämtar resursens datastorlek i byte. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Hämtar eller anger miniatyrbildens dataformat. |
| height | int | r/w | Hämtar eller anger miniatyrbildens höjd i pixlar. |
| id | short | r/w | Hämtar eller anger den unika identifieraren för resursen. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | Hämtar eller anger JPEG-alternativen. Lämplig när miniatyrresursen endast sparas i JPEG-filformat. Detta alternativ har ingen effekt när RAW-format är definierat. |
| minimal_version | int | r | Hämtar den minsta erforderliga PSD-versionen. |
| name | string | r/w | Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0). |
| planes_count | short | r/w | Hämtar eller anger antalet plan. |
| signatur | int | r | Hämtar resursens signatur. Ska alltid vara '8BIM'. |
| storlek | int | r | Hämtar resursblockets storlek i byte inklusive dess data. |
| size_after_compression | int | r | Hämtar eller anger storleken efter komprimering. Används för konsistenskontroll. |
| thumbnail_argb_32_data | int | r/w | Hämtar eller anger 32-bitars ARGB-miniatyrdata. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger miniatyrdata. |
| total_size | int | r | Hämtar den totala datastorleken. |
| width | int | r/w | Hämtar eller anger miniatyrbildens bredd i pixlar. |
| width_bytes | int | r | Hämtar radbredden i byte. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream)](#save_stream_1) | Sparar resursblockets data. |
| validate_values() | Validerar resursvärdena. |


### Constructor: Thumbnail4Resource() {#Thumbnail4Resource__1}


```
 Thumbnail4Resource() 
```

Initierar en ny instans av Thumbnail4Resource-klassen

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Sparar resursblockets data.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

