---
title: CmykColor Class
type: docs
weight: 580
url: /python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.6.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Initializes a new instance of the CmykColor class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| c | byte | r | Gets the cyan component value of this [Color](/psd/python-net/aspose.psd/color/) structure. |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Gets the empty. |
| is_empty | bool | r | Gets a value indicating whether this [Color](/psd/python-net/aspose.psd/color/) structure is uninitialized. |
| k | byte | r | Gets the black component value of this [Color](/psd/python-net/aspose.psd/color/) structure. |
| m | byte | r | Gets the magenta component value of this [Color](/psd/python-net/aspose.psd/color/) structure. |
| y | byte | r | Gets the yellow component value of this [Color](/psd/python-net/aspose.psd/color/) structure. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Creates a [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) structure from a 32-bit cyan, magenta, yellow and black values.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | The conversion from CMYKColor to 32-bit ARGB Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_value()](#to_value__11) | The to value. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Initializes a new instance of the CmykColor class

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Creates a [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) structure from a 32-bit cyan, magenta, yellow and black values.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cyan | int | The cyan component. Valid values are 0 through 255. |
| magenta | int | The magenta component. Valid values are 0 through 255. |
| yellow | int | The yellow component. Valid values are 0 through 255. |
| black | int | The black component. Valid values are 0 through 255. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | The [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

The conversion from CMYKColor to 32-bit ARGB Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| int | The array of the 32-bit ARGB color. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | The <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

The conversion from 32-bit ARGB color to CMYKColor.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int | The pixels of 32-bit ARGB format. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | The <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | The array of the ARGB colors. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

The conversion from CMYKColor to Color using icc conversion  with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | The array of the ARGB colors. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | The [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing icc cmyk profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing icc rgb profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | The [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

The conversion from CMYKColor to Color using icc conversion with default profiles.<br/>            This method is deprecated. Please use more effective [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | The [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYKColor to Color using icc conversion.<br/>            This method is deprecated. Please use more effective Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | The pixels of CMYKColor type in CMYK format. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing icc cmyk profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing icc rgb profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | The [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

The to value.

**Returns**

| Type | Description |
| :- | :- |
| long | The int. |


