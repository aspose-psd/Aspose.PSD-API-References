---
title: "LevlResource-klass"
type: docs
weight: 490
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | Initierar en ny instans av klassen [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/). |
| [LevlResource(bytes)](#LevlResource_bytes_2) | Initierar en ny instans av klassen [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) .<br/>            Stöds i GrayScale, Duotone, RGB, CMYK, Lab-färglägen<br/>            2 byte - Version (=2)<br/>            29 * 10 byte - Uppsättningar av nivåposter med 5 korta heltal<br/>            4 byte - Lvls-header (börjar vid index 292)<br/>            2 byte - Version (=3)<br/>            2 byte - Antal totala nivåposter<br/>            10 * (Totalt antal - 29)<br/>            Nollavslutning av Lvls-resurs bör vara vik för fyra också |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
| version | short | r | Hämtar versionen. Standard är 2 |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Hämtar kanalen. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

Initierar en ny instans av klassen [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

Initierar en ny instans av klassen [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) .<br/>            Stöds i GrayScale, Duotone, RGB, CMYK, Lab-färglägen<br/>            2 byte - Version (=2)<br/>            29 * 10 byte - Uppsättningar av nivåposter med 5 korta heltal<br/>            4 byte - Lvls-header (börjar vid index 292)<br/>            2 byte - Version (=3)<br/>            2 byte - Antal totala nivåposter<br/>            10 * (Totalt antal - 29)<br/>            Nollavslutning av Lvls-resurs bör vara vik för fyra också

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bytes | byte | Byte. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Hämtar kanalen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Nivådata för kanal |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Sparar resursen till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |

