---
title: "ColorPalette-Klasse"
type: docs
weight: 800
url: /de/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Initialisiert eine neue Instanz der [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)-Klasse und IsCompactPalette ist false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Initialisiert eine neue Instanz der [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)-Klasse. |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Initialisiert eine neue Instanz der [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)-Klasse und IsCompactPalette ist false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Initialisiert eine neue Instanz der [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)-Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Gibt ein Array von 32-bit ARGB Strukturen zurück. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Gibt ein Array von [Color](/psd/python-net/aspose.psd/color/) Strukturen zurück. |
| entries_count | int | r | Gibt die Anzahl der Einträge zurück. |
| is_compact_palette | bool | r | Ruft einen Wert ab oder legt ihn fest, der angibt, ob eine kompakte Palette verwendet wird. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Kopiert die Palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Kopiert die Palette. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Gibt die 32-bit ARGB Palettenfarbe nach Index zurück. |
| [get_color(index)](#get_color_index_4) | Gibt die Palettenfarbe nach Index zurück. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Ruft den Index der nächstgelegenen Farbe ab. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Ruft den Index der nächstgelegenen Farbe ab. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Initialisiert eine neue Instanz der [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)-Klasse und IsCompactPalette ist false.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_entries | int | Die 32-Bit-ARGB-Einträge der Farbpalette. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Initialisiert eine neue Instanz der [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)-Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_entries | int | Die 32-Bit-ARGB-Einträge der Farbpalette. |
| is_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Initialisiert eine neue Instanz der [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)-Klasse und IsCompactPalette ist false.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Initialisiert eine neue Instanz der [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)-Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Gibt an, ob die Palette kompakt ist. |

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
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Die neu erstellte und kopierte Palette oder null, wenn eine null-Palette übergeben wurde. |


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
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Die neu erstellte und kopierte Palette oder null, wenn eine null-Palette übergeben wurde. |


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


