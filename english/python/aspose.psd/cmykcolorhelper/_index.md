---
title: CmykColorHelper Class
type: docs
weight: 590
url: /python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.5.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | Creates CMYK from a 32-bit cyan, magenta, yellow and black values. |
| [get_c(cmyk)](#get_c_cmyk_2) | Gets the cyan component value. |
| [get_k(cmyk)](#get_k_cmyk_3) | Gets the black component value. |
| [get_m(cmyk)](#get_m_cmyk_4) | Gets the magenta component value. |
| [get_y(cmyk)](#get_y_cmyk_5) | Gets the yellow component value. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | The conversion from CMYK colors to ARGB colors. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | The conversion from CMYK colors to ARGB colors. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | The conversion from CMYK colors to ARGB colors. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | The conversion from ARGB colors to CMYK colors. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | Converts RGB to CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Converts RGB to CMYK using custom ICC profiles. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

Creates CMYK from a 32-bit cyan, magenta, yellow and black values.

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
| int | The CMYK color presented as a 32-bit integer value. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Gets the cyan component value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns**

| Type | Description |
| :- | :- |
| int | The cyan component value. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Gets the black component value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns**

| Type | Description |
| :- | :- |
| int | The black component value. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Gets the magenta component value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns**

| Type | Description |
| :- | :- |
| int | The magenta component value. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Gets the yellow component value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns**

| Type | Description |
| :- | :- |
| int | The yellow component value. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | The ARGB colors. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | The CMYK colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | The ARGB colors. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | The CMYK colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| int | The ARGB colors presented as 32-bit integer values. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | The ARGB colors. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | The ARGB colors. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | The CMYK pixels presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | The ARGB colors. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | The CMYK colors presented as 32-bit integer values. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | The ARGB colors. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int | The ARGB colors presented as 32-bit integer values. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

The conversion from ARGB colors to CMYK colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Converts RGB to CMYK.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_pixels | int | The RGB colors presented as 32-bit integer values. |
| start_index | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The CMYK colors presented as a byte array. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | The ARGB colors. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | The ARGB colors. |
| rgb_icc_stream | _io.BufferedRandom | The stream containing RGB Icc profile. |
| cmyk_icc_stream | _io.BufferedRandom | The stream containing CMYK Icc profile. |

**Returns**

| Type | Description |
| :- | :- |
| int | The CMYK colors presented as 32-bit integer values. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Converts RGB to CMYK using custom ICC profiles.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels | int | The RGB colors presented as 32-bit integer values. |
| start_index | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |
| rgb_icc_stream | _io.BufferedRandom | The RGB profile stream. |
| cmyk_icc_stream | _io.BufferedRandom | The CMYK profile stream. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The CMYK colors presented as a byte array. |


