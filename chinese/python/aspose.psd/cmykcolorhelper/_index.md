---
title: "CmykColorHelper 类"
type: docs
weight: 640
url: /zh/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | 从 32 位青色、品红、黄色和黑色值创建 CMYK。 |
| [get_c(cmyk)](#get_c_cmyk_2) | 获取青色分量值。 |
| [get_k(cmyk)](#get_k_cmyk_3) | 获取黑色分量值。 |
| [get_m(cmyk)](#get_m_cmyk_4) | 获取品红分量值。 |
| [get_y(cmyk)](#get_y_cmyk_5) | 获取黄色分量值。 |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | CMYK 颜色到 ARGB 颜色的转换。 |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | CMYK 颜色到 ARGB 颜色的转换。 |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | CMYK 颜色到 ARGB 颜色的转换。 |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | 使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | 使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色的过程。 |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | 使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | 使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色的过程。 |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | 将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | 将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | 将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | 将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | 将 RGB 转换为 CMYK。 |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | 使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | 使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色的过程。 |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYK。 |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

从 32 位青色、品红、黄色和黑色值创建 CMYK。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 青色 | int | 青色分量。有效值范围为 0 到 255。 |
| 品红色 | int | 品红分量。有效值范围为 0 到 255。 |
| 黄色 | int | 黄色分量。有效值范围为 0 到 255。 |
| 黑色 | int | 黑色分量。有效值范围为 0 到 255。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 以 32 位整数值表示的 CMYK 颜色。 |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

获取青色分量值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 青色分量值。 |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

获取黑色分量值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 黑色分量的值。 |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

获取品红分量值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 品红色分量的值。 |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

获取黄色分量值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 黄色分量的值。 |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

CMYK 颜色到 ARGB 颜色的转换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB 颜色。 |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

CMYK 颜色到 ARGB 颜色的转换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixels | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB 颜色。 |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

CMYK 颜色到 ARGB 颜色的转换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixels | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 以 32 位整数值表示的 ARGB 颜色。 |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB 颜色。 |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB 颜色。 |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixels | int | 以 32 位整数值表示的 CMYK 像素。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB 颜色。 |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 CMYK 颜色转换为 ARGB 颜色的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixels | int | 以 32 位整数值表示的 CMYK 颜色。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB 颜色。 |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 以 32 位整数值表示的 CMYK 颜色。 |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb_pixels | int | 以 32 位整数值表示的 ARGB 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 以 32 位整数值表示的 CMYK 颜色。 |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 以 32 位整数值表示的 CMYK 颜色。 |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 以 32 位整数值表示的 CMYK 颜色。 |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

将 RGB 转换为 CMYK。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb_pixels | int | 以 32 位整数值表示的 RGB 颜色。 |
| start_index | int | RGB 颜色的起始索引。 |
| 长度 | int | 要转换的 RGB 像素数量。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 以字节数组形式表示的 CMYK 颜色。 |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 以 32 位整数值表示的 CMYK 颜色。 |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 以 32 位整数值表示的 CMYK 颜色。 |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

使用默认配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 以 32 位整数值表示的 CMYK 颜色。 |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义配置文件的 ICC 转换将 ARGB 颜色转换为 CMYK 颜色的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB 颜色。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 RGB Icc 配置文件的流。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 CMYK Icc 配置文件的流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 以 32 位整数值表示的 CMYK 颜色。 |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

使用自定义 ICC 配置文件将 RGB 转换为 CMYK。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pixels | int | 以 32 位整数值表示的 RGB 颜色。 |
| start_index | int | RGB 颜色的起始索引。 |
| 长度 | int | 要转换的 RGB 像素数量。 |
| rgb_icc_stream | _io.BufferedRandom | RGB 配置文件流。 |
| cmyk_icc_stream | _io.BufferedRandom | CMYK 配置文件流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 以字节数组形式表示的 CMYK 颜色。 |


