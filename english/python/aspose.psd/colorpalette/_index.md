---
title: ColorPalette Class
type: docs
weight: 790
url: /python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Initializes a new instance of the [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) class and IsCompactPalette is false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Initializes a new instance of the [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) class. |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Initializes a new instance of the [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) class and IsCompactPalette is false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Initializes a new instance of the [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Gets an array of 32-bit ARGB structures. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Gets an array of [Color](/psd/python-net/aspose.psd/color/) structures. |
| entries_count | int | r | Gets the entries count. |
| is_compact_palette | bool | r | Gets or sets a value indicating whether compact palette is used. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copies the palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copies the palette. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Gets the 32-bit ARGB palette color by index. |
| [get_color(index)](#get_color_index_4) | Gets the palette color by index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Gets the index of the nearest color. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Gets the index of the nearest color. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Initializes a new instance of the [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) class and IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_32_entries | int | The 32-bit ARGB color palette entries. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Initializes a new instance of the [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_32_entries | int | The 32-bit ARGB color palette entries. |
| is_compact_palette | bool | Indicating whether compact it palette. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Initializes a new instance of the [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) class and IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Initializes a new instance of the [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Indicating whether compact it palette. |

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
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | The newly created and copied palette or null if null palette passed. |


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
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | The newly created and copied palette or null if null palette passed. |


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


