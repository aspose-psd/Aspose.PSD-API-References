---
title: "PattResourceData-klass"
type: docs
weight: 780
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | Initierar en ny instans av PattResourceData-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| height | short | r | Hämtar höjden. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | Hämtar bildläget. |
| längd | int | r | Hämtar mönstrets längd. |
| name | string | r/w | Hämtar eller anger namnet. |
| pattern_data | int | r | Hämtar mönsterdata. |
| pattern_id | string | r/w | Hämtar eller anger mönsteridentifieraren. |
| version | int | r | Hämtar versionen. |
| width | short | r | Hämtar bredden. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | Sparar mönsterdata. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | Anger mönstret. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

Initierar en ny instans av PattResourceData-klassen

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

Sparar mönsterdata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

Anger mönstret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int | Pixlarna. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Gränserna. |

