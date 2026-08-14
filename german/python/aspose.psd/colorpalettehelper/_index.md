---
title: "ColorPaletteHelper Klasse"
type: docs
weight: 810
url: /de/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Erstellt die 4-bit Farbpalette. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Erstellt die 4-bit Graustufenpalette. |
| [create_8_bit()](#create_8_bit__3) | Erstellt die 8-bit Farbpalette. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Erstellt die 8-bit Graustufenpalette. |
| [create_monochrome()](#create_monochrome__5) | Erstellt eine monochrome Farbpalette, die nur 2 Farben enthält. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | Erhalte 256-Farbpalette, zusammengesetzt aus den oberen Bits der ursprünglichen Bildfarbwerte. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Erhalte einheitliche 256-Farbpalette. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Bestimmt, ob die angegebene Palette transparente Farben enthält. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Erstellt die 4-bit Farbpalette.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die 4-bit Farbpalette. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Erstellt die 4-bit Graustufenpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| min_is_white | bool | Wenn auf <c>true</c> gesetzt, beginnt die Palette mit weißer Farbe, sonst beginnt sie mit schwarzer Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die 4‑Bit‑Graustufen‑Palette. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Erstellt die 8-bit Farbpalette.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die 8‑Bit‑Farbpalette. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Erstellt die 8-bit Graustufenpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| min_is_white | bool | Wenn auf <c>true</c> gesetzt, beginnt die Palette mit weißer Farbe, sonst beginnt sie mit schwarzer Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die 8‑Bit‑Graustufen‑Palette. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Erstellt eine monochrome Farbpalette, die nur 2 Farben enthält.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Farbpalette für monochrome Bilder. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Das Rasterbild. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die Begrenzungen des Zielbildes. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die Farbpalette, die mit den am häufigsten vorkommenden Farben aus <paramref name="image" /> beginnt und <paramref name="entriesCount" /> Einträge enthält. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Das Rasterbild. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die Begrenzungen des Zielbildes. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |
| use_image_palette | bool | Wenn gesetzt, verwendet es seine eigene Bildpalette, falls verfügbar. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die Farbpalette, die mit den am häufigsten vorkommenden Farben aus <paramref name="image" /> beginnt und <paramref name="entriesCount" /> Einträge enthält. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Das Rasterbild. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die Farbpalette, die mit den am häufigsten vorkommenden Farben aus <paramref name="image" /> beginnt und <paramref name="entriesCount" /> Einträge enthält. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

Erhalte 256-Farbpalette, zusammengesetzt aus den oberen Bits der ursprünglichen Bildfarbwerte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Das Bild. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Die [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Erhalte einheitliche 256-Farbpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Das Bild. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Die [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Bestimmt, ob die angegebene Palette transparente Farben enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die Palette. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn die angegebene Palette transparente Farben hat; andernfalls <c>false</c>. |


