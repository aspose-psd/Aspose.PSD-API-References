---
title: PhflResourceVersion3 Class
type: docs
weight: 760
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion3

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PhflResourceVersion3()](#PhflResourceVersion3__1) | Initializes a new instance of the [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) class. |
| [PhflResourceVersion3(data)](#PhflResourceVersion3_data_2) | Initializes a new instance of the [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| color_space | short | r | Gets the color space. |
| color_x | float | r/w | Gets or sets the X color. |
| color_y | float | r/w | Gets or sets the Y color. |
| color_z | float | r/w | Gets or sets the Z color. |
| density | int | r/w | Gets or sets the density. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| preserve_luminosity | bool | r/w | Gets or sets a value indicating whether [preserve luminosity]. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
| version | short | r | Gets the version. Default is 2 or 3 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Gets the color. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Saves the resource to the specified stream container. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Sets the RGB color. |


### Constructor: PhflResourceVersion3() {#PhflResourceVersion3__1}


```
 PhflResourceVersion3() 
```

Initializes a new instance of the [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) class.

### Constructor: PhflResourceVersion3(data) {#PhflResourceVersion3_data_2}


```
 PhflResourceVersion3(data) 
```

Initializes a new instance of the [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The data of the resource. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Gets the color.

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | The RGB color |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Saves the resource to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |
| psd_version | int | The PSD version. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

Sets the RGB color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | The color. |

