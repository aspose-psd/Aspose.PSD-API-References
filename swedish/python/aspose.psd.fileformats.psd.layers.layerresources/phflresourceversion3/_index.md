---
title: "PhflResourceVersion3-klass"
type: docs
weight: 810
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion3

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PhflResourceVersion3()](#PhflResourceVersion3__1) | Initierar en ny instans av klassen [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/). |
| [PhflResourceVersion3(data)](#PhflResourceVersion3_data_2) | Initierar en ny instans av klassen [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| color_space | short | r | Hämtar färgrymden. |
| color_x | float | r/w | Hämtar eller anger X-färgen. |
| color_y | float | r/w | Hämtar eller anger Y-färgen. |
| color_z | float | r/w | Hämtar eller anger Z-färgen. |
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
| [get_rgb_color()](#get_rgb_color__1) | Hämtar färgen. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Sparar resursen till den angivna strömbehållaren. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Anger RGB-färgen. |


### Constructor: PhflResourceVersion3() {#PhflResourceVersion3__1}


```
 PhflResourceVersion3() 
```

Initierar en ny instans av klassen [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/).

### Constructor: PhflResourceVersion3(data) {#PhflResourceVersion3_data_2}


```
 PhflResourceVersion3(data) 
```

Initierar en ny instans av klassen [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Data för resursen. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Hämtar färgen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | RGB-färgen. |


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
| color | [Color](/psd/python-net/aspose.psd/color) | Färgen. |

