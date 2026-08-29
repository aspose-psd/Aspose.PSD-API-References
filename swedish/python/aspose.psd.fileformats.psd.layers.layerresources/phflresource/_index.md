---
title: "PhflResource-klass"
type: docs
weight: 790
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| densitet | int | r/w | Hämtar eller anger densiteten. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| preserve_luminosity | bool | r/w | Hämtar eller anger ett värde som indikerar om [preserve luminosity]. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
| version | short | r | Hämtar versionen. Standard är 2 eller 3 |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Hämtar färgen för RGB. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Sparar resursen till den angivna strömbehållaren. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Anger RGB-färgen. |


### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Hämtar färgen för RGB.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | RGB-färgen |


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

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

Anger RGB-färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | RGB-färgen. |

