---
title: "ColorPalette-klass"
type: docs
weight: 800
url: /sv/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Initierar en ny instans av klassen [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) och IsCompactPalette är falskt. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Initierar en ny instans av klassen [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Initierar en ny instans av klassen [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) och IsCompactPalette är falskt. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Initierar en ny instans av klassen [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Hämtar en matris av 32-bitars ARGB-strukturer. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Hämtar en matris av [Color](/psd/python-net/aspose.psd/color/) strukturer. |
| entries_count | int | r | Hämtar antalet poster. |
| is_compact_palette | bool | r | Hämtar eller anger ett värde som indikerar om en kompakt palett används. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Kopierar paletten. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Kopierar paletten. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Hämtar 32-bitars ARGB-palettfärgen efter index. |
| [get_color(index)](#get_color_index_4) | Hämtar palettfärgen efter index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Hämtar indexet för den närmaste färgen. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Hämtar indexet för den närmaste färgen. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Initierar en ny instans av klassen [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) och IsCompactPalette är falskt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_entries | int | De 32-bitars ARGB-färgpalettposterna. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Initierar en ny instans av klassen [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_entries | int | De 32-bitars ARGB-färgpalettposterna. |
| is_compact_palette | bool | Anger om paletten är kompakt. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Initierar en ny instans av klassen [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) och IsCompactPalette är falskt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Initierar en ny instans av klassen [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Anger om paletten är kompakt. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Kopierar paletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Färgpaletten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Den nyss skapade och kopierade paletten eller null om en null-palett skickas. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Kopierar paletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Färgpaletten. |
| use_compact_palette | bool | Anger om en kompakt palett. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Den nyss skapade och kopierade paletten eller null om en null-palett skickas. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


```
 get_argb_32_color(index) 
```

Hämtar 32-bitars ARGB-palettfärgen efter index.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | 32-bitars ARGB-palettfärgens index. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Färgpalettposten som anges av <paramref name="index" />. |


### Method: get_color(index) {#get_color_index_4}


```
 get_color(index) 
```

Hämtar palettfärgen efter index.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Palettfärgens index. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Färgpalettposten som anges av <paramref name="index" />. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

Hämtar indexet för den närmaste färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_color | int | Den 32-bitars ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Index för den närmaste färgen. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

Hämtar indexet för den närmaste färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Index för den närmaste färgen. |


