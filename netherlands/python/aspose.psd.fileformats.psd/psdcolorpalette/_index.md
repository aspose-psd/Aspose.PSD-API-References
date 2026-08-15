---
title: "PsdColorPalette Klasse"
type: docs
weight: 1750
url: /nl/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse. |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse. |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse. |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse en IsCompactPalette is false. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse. |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse en IsCompactPalette is false. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse. |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse en IsCompactPalette is false. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse. |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse en IsCompactPalette is false. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Haalt een array op van 32-bit ARGB-kleuren. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Haalt een array op van [Color](/psd/python-net/aspose.psd/color/) structuren. |
| entries_count | int | r | Haalt het aantal vermeldingen op. |
| has_transparent_color | bool | r | Haalt een waarde op die aangeeft of er een transparante kleur bestaat. |
| is_compact_palette | bool | r | Haalt een waarde op die aangeeft of de palet compact is. |
| raw_entries | byte | r | Haalt de ruwe gegevens van de kleurpaletvermeldingen op. |
| raw_entries_count | int | r | Haalt het aantal ruwe kleurpaletvermeldingen op. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Haalt de transparante kleur op. |
| transparent_index | short | r | Haalt de index van de transparante kleur op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Kopieert het palet. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Kopieert het palet. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Haalt de 32-bit ARGB-paletkleur op basis van index. |
| [get_color(index)](#get_color_index_4) | Haalt de paletkleur op basis van index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Haalt de index van de dichtstbijzijnde kleur op. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Haalt de index van de dichtstbijzijnde kleur op. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het kleurenpalet. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het kleurenpalet. |
| transparent_index | short | De transparante kleurindex. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_palette_argb_32_entries | int | Het kleurenpalet 32-bit ARGB-items. |
| is_compact_palette | bool | Geeft aan of het palet compact is. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse en IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | De kleurenpalet-items. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | De kleurenpalet-items. |
| is_compact_palette | bool | Geeft aan of het palet compact is. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse en IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | De kleurenpalet-items. |
| transparent_index | short | De transparante kleurindex. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | De kleurenpalet-items. |
| transparent_index | short | De transparante kleurindex. |
| use_compact_palette | bool | Geeft aan of het palet compact is. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse en IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| raw_entries_data | byte | De ruwe itemsgegevens. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| raw_entries_data | byte | De ruwe itemsgegevens. |
| is_compact_palette | bool | Geeft aan of het palet compact is. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse en IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| raw_entries_data | byte | De ruwe itemsgegevens. |
| transparent_index | short | De index van de transparante kleur. Merk op dat de index niet de index van de ruwe items is, maar voor de geconverteerde kleurenarray. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Initialiseert een nieuw exemplaar van de [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| raw_entries_data | byte | De ruwe itemsgegevens. |
| transparent_index | short | De index van de transparante kleur. Merk op dat de index niet de index van de ruwe items is, maar voor de geconverteerde kleurenarray. |
| use_compact_palette | bool | Geeft aan of het palet compact is. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Het nieuw aangemaakte en gekopieerde palet of null als een null-palet werd doorgegeven. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Het nieuw aangemaakte en gekopieerde palet of null als een null-palet werd doorgegeven. |


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


