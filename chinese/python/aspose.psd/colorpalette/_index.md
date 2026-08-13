---
title: "ColorPalette 类"
type: docs
weight: 800
url: /zh/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | 初始化 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 类的新实例，且 IsCompactPalette 为 false。 |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | 初始化 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 类的新实例。 |
| [ColorPalette(entries)](#ColorPalette_entries_3) | 初始化 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 类的新实例，且 IsCompactPalette 为 false。 |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | 初始化 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 获取 32 位 ARGB 结构的数组。 |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | 获取 [Color](/psd/python-net/aspose.psd/color/) 结构的数组。 |
| entries_count | int | r | 获取条目计数。 |
| is_compact_palette | bool | r | 获取或设置一个值，指示是否使用紧凑调色板。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | 复制调色板。 |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | 复制调色板。 |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | 按索引获取 32 位 ARGB 调色板颜色。 |
| [get_color(index)](#get_color_index_4) | 按索引获取调色板颜色。 |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | 获取最近颜色的索引。 |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | 获取最近颜色的索引。 |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

初始化 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 类的新实例，且 IsCompactPalette 为 false。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb_32_entries | int | 32 位 ARGB 颜色调色板条目。 |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

初始化 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb_32_entries | int | 32 位 ARGB 颜色调色板条目。 |
| is_compact_palette | bool | 指示调色板是否紧凑。 |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

初始化 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 类的新实例，且 IsCompactPalette 为 false。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

初始化 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | 指示调色板是否紧凑。 |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

复制调色板。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 颜色调色板。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | 如果传入空调色板，则返回新创建和复制的调色板，否则为 null。 |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

复制调色板。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 颜色调色板。 |
| use_compact_palette | bool | 指示调色板是否紧凑。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | 如果传入空调色板，则返回新创建和复制的调色板，否则为 null。 |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


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


### Method: get_color(index) {#get_color_index_4}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

获取最近颜色的索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb_32_color | int | 32 位 ARGB 颜色。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 最近颜色的索引。 |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

获取最近颜色的索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 最近颜色的索引。 |


