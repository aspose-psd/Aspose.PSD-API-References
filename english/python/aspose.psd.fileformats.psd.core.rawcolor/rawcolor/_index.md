---
title: RawColor Class
type: docs
weight: 20
url: /python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Initializes a new instance of the [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) class. |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Initializes a new instance of the [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) class from pixel data format using predefined color modes |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Mode for the color to follow. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Gets the components of color. Each component is separate channel, and if you use not popular<br/>            color scheme, it's better to work with each channel separately. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Gets the color as int in case it's possible to get it. |
| [get_as_long()](#get_as_long__2) | Gets the color as long in case it's possible to get it. |
| [get_bit_depth()](#get_bit_depth__3) | Gets the bit depth of Raw Color. <br/>            For example for ARGB color with 8 bits per channel/component is 32<br/>            Bit Depth of full ARGB color with 16 bits per channel/component is 64.<br/>            Bit depth is accumulated from the sum of channels' bit depths. <br/>            It's possible if different channels will have different bit depths. |
| [get_color_mode_name()](#get_color_mode_name__4) | Gets the name of the color mode. Color mode name accumulated from channels/components names |
| [set_as_int(value)](#set_as_int_value_5) | Sets data to all channels from int argument if it's possible |
| [set_as_long(value)](#set_as_long_value_6) | Sets data to all channels from int argument if it's possible |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Initializes a new instance of the [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | The custom color components. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Initializes a new instance of the [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) class from pixel data format using predefined color modes

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | The pixel data format. |
| color_mode | short | Mode for the color to follow. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Gets the color as int in case it's possible to get it.

**Returns**

| Type | Description |
| :- | :- |
| int | Channels data stored in Int |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Gets the color as long in case it's possible to get it.

**Returns**

| Type | Description |
| :- | :- |
| long | Channels data stored in Int |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Gets the bit depth of Raw Color. <br/>            For example for ARGB color with 8 bits per channel/component is 32<br/>            Bit Depth of full ARGB color with 16 bits per channel/component is 64.<br/>            Bit depth is accumulated from the sum of channels' bit depths. <br/>            It's possible if different channels will have different bit depths.

**Returns**

| Type | Description |
| :- | :- |
| int | The sum of all channels bit depths |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Gets the name of the color mode. Color mode name accumulated from channels/components names

**Returns**

| Type | Description |
| :- | :- |
| string | String with the color mode name |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Sets data to all channels from int argument if it's possible

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | int | The int value that contains component data |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Sets data to all channels from int argument if it's possible

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | long | The int value that contains component data |

