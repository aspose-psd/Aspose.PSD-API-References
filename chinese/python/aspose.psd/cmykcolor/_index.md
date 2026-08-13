---
title: "CmykColor 类"
type: docs
weight: 630
url: /zh/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | 初始化 CmykColor 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| c | byte | r | 获取此 [Color](/psd/python-net/aspose.psd/color/) 结构的青色分量值。 |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | 获取空值。 |
| is_empty | bool | r | 获取一个值，指示此 [Color](/psd/python-net/aspose.psd/color/) 结构是否未初始化。 |
| k | byte | r | 获取此 [Color](/psd/python-net/aspose.psd/color/) 结构的黑色分量值。 |
| m | byte | r | 获取此 [Color](/psd/python-net/aspose.psd/color/) 结构的品红分量值。 |
| y | byte | r | 获取此 [Color](/psd/python-net/aspose.psd/color/) 结构的黄色分量值。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | 从 32 位青色、品红色、黄色和黑色值创建一个 [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) 结构。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/)。 |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | 使用默认配置文件的 ICC 转换将 CMYKColor 转换为 32 位 ARGB Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。 |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | 将 32 位 ARGB 颜色转换为 CMYKColor。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。 |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | 将 32 位 ARGB 颜色转换为 CMYKColor。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。 |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | 使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。 |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | 使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。 |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | 使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。 |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | 使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom)。 |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | 使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。 |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | 使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom)。 |
| [to_value()](#to_value__11) | to 值。 |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

初始化 CmykColor 类的新实例

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

从 32 位青色、品红色、黄色和黑色值创建一个 [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) 结构。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/)。

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
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | 此 [CmykColor](/psd/python-net/aspose.psd/cmykcolor/)。 |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

使用默认配置文件的 ICC 转换将 CMYKColor 转换为 32 位 ARGB Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 32 位 ARGB 颜色的数组。 |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

将 32 位 ARGB 颜色转换为 CMYKColor。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | 此 <see cref="T:Aspose:PSD:CmykColor[]" />。 |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

将 32 位 ARGB 颜色转换为 CMYKColor。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb_pixels | int | 32 位 ARGB 格式的像素。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | 此 <see cref="T:Aspose:PSD:CmykColor[]" />。 |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB 颜色的数组。 |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB 颜色的数组。 |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 该 [Color[]](/psd/python-net/aspose.psd/color/)。 |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | 包含 icc cmyk 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 icc rgb 配置文件的流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 该 [Color[]](/psd/python-net/aspose.psd/color/)。 |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

使用默认配置文件的 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | 该 [Color[]](/psd/python-net/aspose.psd/color/)。 |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

使用 ICC 转换将 CMYKColor 转换为 Color。<br/>            此方法已弃用。请使用更有效的 Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |
| cmyk_icc_stream | _io.BufferedRandom | 包含 icc cmyk 配置文件的流。 |
| rgb_icc_stream | _io.BufferedRandom | 包含 icc rgb 配置文件的流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | 该 [Color[]](/psd/python-net/aspose.psd/color/)。 |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

to 值。

**Returns**

| 类型 | 描述 |
| :- | :- |
| long | 该 int。 |


