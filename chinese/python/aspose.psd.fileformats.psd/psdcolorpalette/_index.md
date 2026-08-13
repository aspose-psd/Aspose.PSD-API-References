---
title: "PsdColorPalette 类"
type: docs
weight: 1750
url: /zh/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。 |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。 |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。 |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例，并且 IsCompactPalette 为 false。 |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。 |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例，并且 IsCompactPalette 为 false。 |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。 |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例，并且 IsCompactPalette 为 false。 |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。 |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例，并且 IsCompactPalette 为 false。 |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | 初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 获取一个 32 位 ARGB 颜色的数组。 |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | 获取 [Color](/psd/python-net/aspose.psd/color/) 结构的数组。 |
| entries_count | int | r | 获取条目计数。 |
| has_transparent_color | bool | r | 获取指示透明颜色是否存在的值。 |
| is_compact_palette | bool | r | 获取一个指示调色板是否紧凑的值。 |
| raw_entries | byte | r | 获取原始颜色调色板条目数据。 |
| raw_entries_count | int | r | 获取原始颜色调色板条目计数。 |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | 获取透明颜色。 |
| transparent_index | short | r | 获取透明颜色的索引。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | 复制调色板。 |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | 复制调色板。 |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | 按索引获取 32 位 ARGB 调色板颜色。 |
| [get_color(index)](#get_color_index_4) | 按索引获取调色板颜色。 |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | 获取最近颜色的索引。 |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | 获取最近颜色的索引。 |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 颜色调色板。 |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 颜色调色板。 |
| transparent_index | short | 透明颜色索引。 |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color_palette_argb_32_entries | int | 颜色调色板的 32 位 ARGB 条目。 |
| is_compact_palette | bool | 指示调色板是否紧凑。 |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | 颜色调色板条目。 |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | 颜色调色板条目。 |
| is_compact_palette | bool | 指示调色板是否紧凑。 |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | 颜色调色板条目。 |
| transparent_index | short | 透明颜色索引。 |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | 颜色调色板条目。 |
| transparent_index | short | 透明颜色索引。 |
| use_compact_palette | bool | 指示调色板是否紧凑。 |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| raw_entries_data | byte | 原始条目数据。 |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| raw_entries_data | byte | 原始条目数据。 |
| is_compact_palette | bool | 指示调色板是否紧凑。 |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| raw_entries_data | byte | 原始条目数据。 |
| transparent_index | short | 透明颜色索引。注意，该索引不是原始条目索引，而是针对转换后的颜色数组的索引。 |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

初始化 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| raw_entries_data | byte | 原始条目数据。 |
| transparent_index | short | 透明颜色索引。注意，该索引不是原始条目索引，而是针对转换后的颜色数组的索引。 |
| use_compact_palette | bool | 指示调色板是否紧凑。 |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | 如果传入空调色板，则返回新创建和复制的调色板，否则为 null。 |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | 如果传入空调色板，则返回新创建和复制的调色板，否则为 null。 |


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


