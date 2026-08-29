---
title: "Classe PsdColorPalette"
type: docs
weight: 1750
url: /fr/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) et IsCompactPalette est false. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) et IsCompactPalette est false. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) et IsCompactPalette est false. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) et IsCompactPalette est false. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Obtient un tableau de couleurs ARGB 32 bits. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Obtient un tableau de structures [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Obtient le nombre d'entrées. |
| a_couleur_transparente | bool | r | Obtient une valeur indiquant si une couleur transparente existe. |
| is_compact_palette | bool | r | Obtient une valeur indiquant si la palette est compacte. |
| raw_entries | byte | r | Obtient les données brutes des entrées de la palette de couleurs. |
| raw_entries_count | int | r | Obtient le nombre d'entrées brutes de la palette de couleurs. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Obtient la couleur transparente. |
| transparent_index | short | r | Obtient l'index de la couleur transparente. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copie la palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copie la palette. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Obtient la couleur de la palette ARGB 32 bits par index. |
| [get_color(index)](#get_color_index_4) | Obtient la couleur de la palette par index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Obtient l'index de la couleur la plus proche. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Obtient l'index de la couleur la plus proche. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de couleurs. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de couleurs. |
| transparent_index | short | L'index de couleur transparente. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette_argb_32_entries | int | Les entrées de la palette de couleurs 32 bits ARGB. |
| is_compact_palette | bool | Indiquant si la palette est compacte. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) et IsCompactPalette est false.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Les entrées de la palette de couleurs. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Les entrées de la palette de couleurs. |
| is_compact_palette | bool | Indiquant si la palette est compacte. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) et IsCompactPalette est false.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Les entrées de la palette de couleurs. |
| transparent_index | short | L'index de couleur transparente. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Les entrées de la palette de couleurs. |
| transparent_index | short | L'index de couleur transparente. |
| use_compact_palette | bool | Indiquant si la palette est compacte. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) et IsCompactPalette est false.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| raw_entries_data | byte | Les données des entrées brutes. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| raw_entries_data | byte | Les données des entrées brutes. |
| is_compact_palette | bool | Indiquant si la palette est compacte. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) et IsCompactPalette est false.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| raw_entries_data | byte | Les données des entrées brutes. |
| transparent_index | short | L'index de couleur transparente. Notez que l'index n'est pas l'index des entrées brutes, il correspond plutôt au tableau de couleurs converties. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Initialise une nouvelle instance de la classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| raw_entries_data | byte | Les données des entrées brutes. |
| transparent_index | short | L'index de couleur transparente. Notez que l'index n'est pas l'index des entrées brutes, il correspond plutôt au tableau de couleurs converties. |
| use_compact_palette | bool | Indiquant si la palette est compacte. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | La palette nouvellement créée et copiée ou null si une palette null est passée. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | La palette nouvellement créée et copiée ou null si une palette null est passée. |


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


