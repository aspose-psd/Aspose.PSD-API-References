---
title: PattResourceData Class
type: docs
weight: 730
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.4.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | Initializes a new instance of the PattResourceData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| height | short | r | Gets the height. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | Gets the image mode. |
| length | int | r | Gets the length of the pattern. |
| name | string | r/w | Gets or sets the name. |
| pattern_data | int | r | Gets the pattern data. |
| pattern_id | string | r/w | Gets or sets the pattern identifier. |
| version | int | r | Gets the version. |
| width | short | r | Gets the width. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | Saves the pattern data. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | Sets the pattern. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

Initializes a new instance of the PattResourceData class

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

Saves the pattern data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

Sets the pattern.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int | The pixels. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The bounds. |

