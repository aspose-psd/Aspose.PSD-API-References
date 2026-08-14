---
title: "PsdColorPalette Klasse"
type: docs
weight: 1750
url: /de/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse. |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse. |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse. |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) und IsCompactPalette ist false. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse. |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) und IsCompactPalette ist false. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse. |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) und IsCompactPalette ist false. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse. |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) und IsCompactPalette ist false. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Gibt ein Array von 32‑Bit‑ARGB‑Farben zurück. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Gibt ein Array von [Color](/psd/python-net/aspose.psd/color/) Strukturen zurück. |
| entries_count | int | r | Gibt die Anzahl der Einträge zurück. |
| has_transparent_color | bool | r | Gibt einen Wert zurück, der angibt, ob eine transparente Farbe existiert. |
| is_compact_palette | bool | r | Gibt einen Wert zurück, der angibt, ob die Palette kompakt ist. |
| raw_entries | byte | r | Gibt die Rohdaten der Farbpalletteinträge zurück. |
| raw_entries_count | int | r | Gibt die Anzahl der Rohfarbpalletteinträge zurück. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Gibt die transparente Farbe zurück. |
| transparent_index | short | r | Gibt den Index der transparenten Farbe zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Kopiert die Palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Kopiert die Palette. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Gibt die 32-bit ARGB Palettenfarbe nach Index zurück. |
| [get_color(index)](#get_color_index_4) | Gibt die Palettenfarbe nach Index zurück. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Ruft den Index der nächstgelegenen Farbe ab. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Ruft den Index der nächstgelegenen Farbe ab. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die Farbpalette. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die Farbpalette. |
| transparent_index | short | Der Index der transparenten Farbe. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette_argb_32_entries | int | Die 32‑Bit‑ARGB‑Einträge der Farbpalette. |
| is_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Initialisiert eine neue Instanz der Klasse [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) und IsCompactPalette ist false.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Die Einträge der Farbpalette. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Die Einträge der Farbpalette. |
| is_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Initialisiert eine neue Instanz der Klasse [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) und IsCompactPalette ist false.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Die Einträge der Farbpalette. |
| transparent_index | short | Der Index der transparenten Farbe. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Die Einträge der Farbpalette. |
| transparent_index | short | Der Index der transparenten Farbe. |
| use_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Initialisiert eine neue Instanz der Klasse [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) und IsCompactPalette ist false.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raw_entries_data | byte | Die Rohdaten der Einträge. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raw_entries_data | byte | Die Rohdaten der Einträge. |
| is_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Initialisiert eine neue Instanz der Klasse [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) und IsCompactPalette ist false.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raw_entries_data | byte | Die Rohdaten der Einträge. |
| transparent_index | short | Der Index der transparenten Farbe. Hinweis: Der Index ist nicht der Index der Rohdaten, sondern bezieht sich auf das konvertierte Farbarray. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Initialisiert eine neue Instanz der [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raw_entries_data | byte | Die Rohdaten der Einträge. |
| transparent_index | short | Der Index der transparenten Farbe. Hinweis: Der Index ist nicht der Index der Rohdaten, sondern bezieht sich auf das konvertierte Farbarray. |
| use_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Kopiert die Palette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die Farbpalette. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Die neu erstellte und kopierte Palette oder null, wenn eine null-Palette übergeben wurde. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Kopiert die Palette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die Farbpalette. |
| use_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Die neu erstellte und kopierte Palette oder null, wenn eine null-Palette übergeben wurde. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


```
 get_argb_32_color(index) 
```

Gibt die 32-bit ARGB Palettenfarbe nach Index zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der 32-bit ARGB Palettenfarbindex. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Farbpalletteintrag, der durch das <paramref name="index" /> angegeben ist. |


### Method: get_color(index) {#get_color_index_4}


```
 get_color(index) 
```

Gibt die Palettenfarbe nach Index zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Palettenfarbindex. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Der Farbpalletteintrag, der durch das <paramref name="index" /> angegeben ist. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

Ruft den Index der nächstgelegenen Farbe ab.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_color | int | Die 32‑Bit‑ARGB‑Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Index der nächsten Farbe. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

Ruft den Index der nächstgelegenen Farbe ab.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Index der nächsten Farbe. |


