---
title: "ColorPalette-klasse"
type: docs
weight: 800
url: /nl/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Initialiseert een nieuw exemplaar van de [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) klasse en IsCompactPalette is false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Initialiseert een nieuw exemplaar van de [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) klasse. |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Initialiseert een nieuw exemplaar van de [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) klasse en IsCompactPalette is false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Initialiseert een nieuw exemplaar van de [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Haalt een array op van 32-bit ARGB-structuren. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Haalt een array op van [Color](/psd/python-net/aspose.psd/color/) structuren. |
| entries_count | int | r | Haalt het aantal vermeldingen op. |
| is_compact_palette | bool | r | Haalt op of stelt een waarde in die aangeeft of een compacte palet wordt gebruikt. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Kopieert het palet. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Kopieert het palet. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Haalt de 32-bit ARGB-paletkleur op basis van index. |
| [get_color(index)](#get_color_index_4) | Haalt de paletkleur op basis van index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Haalt de index van de dichtstbijzijnde kleur op. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Haalt de index van de dichtstbijzijnde kleur op. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Initialiseert een nieuw exemplaar van de [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) klasse en IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb_32_entries | int | De 32-bits ARGB-kleurenpaletvermeldingen. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Initialiseert een nieuw exemplaar van de [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb_32_entries | int | De 32-bits ARGB-kleurenpaletvermeldingen. |
| is_compact_palette | bool | Geeft aan of het palet compact is. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Initialiseert een nieuw exemplaar van de [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) klasse en IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Initialiseert een nieuw exemplaar van de [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Geeft aan of het palet compact is. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Kopieert het palet.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het kleurenpalet. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Het nieuw aangemaakte en gekopieerde palet of null als een null-palet werd doorgegeven. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Kopieert het palet.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het kleurenpalet. |
| use_compact_palette | bool | Geeft aan of het palet compact is. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Het nieuw aangemaakte en gekopieerde palet of null als een null-palet werd doorgegeven. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


```
 get_argb_32_color(index) 
```

Haalt de 32-bit ARGB-paletkleur op basis van index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | De 32-bit ARGB-paletkleurindex. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Het paletitem gespecificeerd door de <paramref name="index" />. |


### Method: get_color(index) {#get_color_index_4}


```
 get_color(index) 
```

Haalt de paletkleur op basis van index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | De paletkleurindex. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Het paletitem gespecificeerd door de <paramref name="index" />. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

Haalt de index van de dichtstbijzijnde kleur op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb_32_color | int | De 32-bit ARGB-kleur. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De index van de dichtstbijzijnde kleur. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

Haalt de index van de dichtstbijzijnde kleur op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De index van de dichtstbijzijnde kleur. |


