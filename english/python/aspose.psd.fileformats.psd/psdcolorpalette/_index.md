---
title: PsdColorPalette Class
type: docs
weight: 1680
url: /python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class. |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class. |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class. |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class and IsCompactPalette is false. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class. |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class and IsCompactPalette is false. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class. |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class and IsCompactPalette is false. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class. |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class and IsCompactPalette is false. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Gets an array of 32-bit ARGB colors. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Gets an array of [Color](/psd/python-net/aspose.psd/color/) structures. |
| entries_count | int | r | Gets the entries count. |
| has_transparent_color | bool | r | Gets a value indicating whether transparent color exists. |
| is_compact_palette | bool | r | Gets a value indicating whether compact it palette. |
| raw_entries | byte | r | Gets the raw color palette entries data. |
| raw_entries_count | int | r | Gets the raw color palette entries count. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Gets the transparent color. |
| transparent_index | short | r | Gets the index of the transparent color. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copies the palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copies the palette. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Gets the 32-bit ARGB palette color by index. |
| [get_color(index)](#get_color_index_4) | Gets the palette color by index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Gets the index of the nearest color. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Gets the index of the nearest color. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The color palette. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The color palette. |
| transparent_index | short | The transparent color index. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette_argb_32_entries | int | The color palette 32-bit ARGB entries. |
| is_compact_palette | bool | Indicating whether compact it palette. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class and IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | The color palette entries. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | The color palette entries. |
| is_compact_palette | bool | Indicating whether compact it palette. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class and IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | The color palette entries. |
| transparent_index | short | The transparent color index. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | The color palette entries. |
| transparent_index | short | The transparent color index. |
| use_compact_palette | bool | Indicating whether compact it palette. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class and IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raw_entries_data | byte | The raw entries data. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raw_entries_data | byte | The raw entries data. |
| is_compact_palette | bool | Indicating whether compact it palette. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class and IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raw_entries_data | byte | The raw entries data. |
| transparent_index | short | The transparent color index. Note the index is not the raw entries index instead it is for the converted color array. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Initializes a new instance of the [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raw_entries_data | byte | The raw entries data. |
| transparent_index | short | The transparent color index. Note the index is not the raw entries index instead it is for the converted color array. |
| use_compact_palette | bool | Indicating whether compact it palette. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Copies the palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The color palette. |

**Returns**

| Type | Description |
| :- | :- |
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | The newly created and copied palette or null if null palette passed. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Copies the palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The color palette. |
| use_compact_palette | bool | Indicating whether compact palette. |

**Returns**

| Type | Description |
| :- | :- |
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | The newly created and copied palette or null if null palette passed. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


```
 get_argb_32_color(index) 
```

Gets the 32-bit ARGB palette color by index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The 32-bit ARGB palette color index. |

**Returns**

| Type | Description |
| :- | :- |
| int | The color palette entry specified by the <paramref name="index" />. |


### Method: get_color(index) {#get_color_index_4}


```
 get_color(index) 
```

Gets the palette color by index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The palette color index. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | The color palette entry specified by the <paramref name="index" />. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

Gets the index of the nearest color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_32_color | int | The 32-bit ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The index of the nearest color. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

Gets the index of the nearest color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The index of the nearest color. |


