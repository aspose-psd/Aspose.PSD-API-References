---
title: "Classe ColorPalette"
type: docs
weight: 800
url: /fr/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Initialise une nouvelle instance de la classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) et IsCompactPalette est false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Initialise une nouvelle instance de la classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Initialise une nouvelle instance de la classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) et IsCompactPalette est false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Initialise une nouvelle instance de la classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Obtient un tableau de structures ARGB 32 bits. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Obtient un tableau de structures [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Obtient le nombre d'entrées. |
| is_compact_palette | bool | r | Obtient ou définit une valeur indiquant si une palette compacte est utilisée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copie la palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copie la palette. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Obtient la couleur de la palette ARGB 32 bits par index. |
| [get_color(index)](#get_color_index_4) | Obtient la couleur de la palette par index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Obtient l'index de la couleur la plus proche. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Obtient l'index de la couleur la plus proche. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) et IsCompactPalette est false.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_32_entries | int | Les entrées de la palette de couleurs ARGB 32 bits. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_32_entries | int | Les entrées de la palette de couleurs ARGB 32 bits. |
| is_compact_palette | bool | Indiquant si la palette est compacte. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) et IsCompactPalette est false.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Initialise une nouvelle instance de la classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Indiquant si la palette est compacte. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Copie la palette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de couleurs. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | La palette nouvellement créée et copiée ou null si une palette null est passée. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Copie la palette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de couleurs. |
| use_compact_palette | bool | Indiquant si la palette est compacte. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | La palette nouvellement créée et copiée ou null si une palette null est passée. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


```
 get_argb_32_color(index) 
```

Obtient la couleur de la palette ARGB 32 bits par index.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de couleur de la palette ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | L'entrée de la palette de couleurs spécifiée par le <paramref name="index" />. |


### Method: get_color(index) {#get_color_index_4}


```
 get_color(index) 
```

Obtient la couleur de la palette par index.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de couleur de la palette. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | L'entrée de la palette de couleurs spécifiée par le <paramref name="index" />. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

Obtient l'index de la couleur la plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_32_color | int | La couleur ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | L'index de la couleur la plus proche. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

Obtient l'index de la couleur la plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | L'index de la couleur la plus proche. |


