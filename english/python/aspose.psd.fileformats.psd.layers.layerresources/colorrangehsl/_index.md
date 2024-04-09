---
title: ColorRangeHsl Class
type: docs
weight: 140
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.2.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Initializes a new instance of the [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) class. |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Initializes a new instance of the [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| hue | short | r/w | Gets or sets the hue. |
| left_border | short | r/w | Gets or sets the left border. |
| lightness | short | r/w | Gets or sets the lightness. |
| most_left_border | short | r/w | Gets or sets the most left border. |
| most_right_border | short | r/w | Gets or sets the most right border. |
| right_border | short | r/w | Gets or sets the right border. |
| saturation | short | r/w | Gets or sets the saturation. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Gets the range Coefficient. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Determines whether is hue in big range. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Determines whether hue in small range. |
| [save(stream_container)](#save_stream_container_4) | Saves data to the specified stream container. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Initializes a new instance of the [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) class.

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Initializes a new instance of the [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The color range data. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Gets the range Coefficient.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| hue | double | The hue value. |

**Returns**

| Type | Description |
| :- | :- |
| double | Saturation range coefficient. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Determines whether is hue in big range.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| hue | double | The hue value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if hue in big range; otherwise, <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Determines whether hue in small range.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| hue | double | The hue value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if hue in small range; otherwise, <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Saves data to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container. |

