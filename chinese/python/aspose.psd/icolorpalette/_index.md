---
title: "IColorPalette 类"
type: docs
weight: 1710
url: /zh/python-net/aspose.psd/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 获取 32 位 ARGB 结构的数组。 |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | 获取 [Color](/psd/python-net/aspose.psd/color/) 结构的数组。 |
| entries_count | int | r | 获取条目计数。 |
| is_compact_palette | bool | r | 获取指示是否使用紧凑调色板的值。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | 按索引获取 32 位 ARGB 调色板颜色。 |
| [get_color(index)](#get_color_index_2) | 按索引获取调色板颜色。 |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | 获取最近的 32 位 ARGB 颜色的索引。 |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | 获取最近的 32 位 ARGB 颜色的索引。 |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

按索引获取 32 位 ARGB 调色板颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 32 位 ARGB 调色板颜色索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 由 <paramref name="index" /> 指定的调色板颜色条目。 |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

按索引获取调色板颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 调色板颜色索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 由 <paramref name="index" /> 指定的调色板颜色条目。 |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

获取最近的 32 位 ARGB 颜色的索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb_32_color | int | 32 位 ARGB 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 最近颜色的索引。 |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

获取最近的 32 位 ARGB 颜色的索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 最近颜色的索引。 |


