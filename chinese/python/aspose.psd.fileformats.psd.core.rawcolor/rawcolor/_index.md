---
title: "RawColor 类"
type: docs
weight: 20
url: /zh/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | 初始化 [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) 类的新实例。 |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | 使用预定义的颜色模式，从像素数据格式初始化 [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_mode | short | 读/写 | 颜色遵循的模式。 |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | 获取颜色的组成部分。每个组成部分都是独立的通道，如果使用不常见的<br/>            颜色方案，最好分别处理每个通道。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | 获取颜色的 int 值（如果可能获取）。 |
| [get_as_long()](#get_as_long__2) | 获取颜色的 long 值（如果可能获取）。 |
| [get_bit_depth()](#get_bit_depth__3) | 获取原始颜色的位深度。 <br/> 例如，对于每通道/组件为 8 位的 ARGB 颜色，位深度为 32<br/> 每通道/组件为 16 位的完整 ARGB 颜色的位深度为 64。<br/> 位深度是从各通道位深度之和累积得到的。 <br/> 如果不同通道具有不同的位深度，则是可能的。 |
| [get_color_mode_name()](#get_color_mode_name__4) | 获取颜色模式的名称。颜色模式名称由通道/组件名称累积而成 |
| [set_as_int(value)](#set_as_int_value_5) | 如果可能，从 int 参数设置所有通道的数据 |
| [set_as_long(value)](#set_as_long_value_6) | 如果可能，从 int 参数设置所有通道的数据 |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

初始化 [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | 自定义颜色组件。 |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

使用预定义的颜色模式，从像素数据格式初始化 [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | 像素数据格式。 |
| color_mode | short | 颜色遵循的模式。 |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

获取颜色的 int 值（如果可能获取）。

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 通道数据以 Int 存储 |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

获取颜色的 long 值（如果可能获取）。

**Returns**

| 类型 | 描述 |
| :- | :- |
| long | 通道数据以 Int 存储 |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

获取原始颜色的位深度。 <br/> 例如，对于每通道/组件为 8 位的 ARGB 颜色，位深度为 32<br/> 每通道/组件为 16 位的完整 ARGB 颜色的位深度为 64。<br/> 位深度是从各通道位深度之和累积得到的。 <br/> 如果不同通道具有不同的位深度，则是可能的。

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 所有通道位深度的总和 |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

获取颜色模式的名称。颜色模式名称由通道/组件名称累积而成

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 包含颜色模式名称的字符串 |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

如果可能，从 int 参数设置所有通道的数据

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | int | 包含组件数据的 int 值 |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

如果可能，从 int 参数设置所有通道的数据

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | long | 包含组件数据的 int 值 |

