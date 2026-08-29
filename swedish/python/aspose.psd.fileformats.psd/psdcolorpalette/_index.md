---
title: "PsdColorPalette-klass"
type: docs
weight: 1750
url: /sv/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) och IsCompactPalette är falskt. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) och IsCompactPalette är falskt. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) och IsCompactPalette är falskt. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) och IsCompactPalette är falskt. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Hämtar en array med 32-bit ARGB-färger. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Hämtar en matris av [Color](/psd/python-net/aspose.psd/color/) strukturer. |
| entries_count | int | r | Hämtar antalet poster. |
| has_transparent_color | bool | r | Hämtar ett värde som indikerar om en transparent färg finns. |
| is_compact_palette | bool | r | Hämtar ett värde som indikerar om paletten är kompakt. |
| raw_entries | byte | r | Hämtar de råa färgpalettposternas data. |
| raw_entries_count | int | r | Hämtar antalet råa färgpalettposter. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Hämtar den transparenta färgen. |
| transparent_index | short | r | Hämtar indexet för den transparenta färgen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Kopierar paletten. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Kopierar paletten. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Hämtar 32-bitars ARGB-palettfärgen efter index. |
| [get_color(index)](#get_color_index_4) | Hämtar palettfärgen efter index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Hämtar indexet för den närmaste färgen. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Hämtar indexet för den närmaste färgen. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Färgpaletten. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Färgpaletten. |
| transparent_index | short | Det transparenta färgindexet. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette_argb_32_entries | int | Färgpalettens 32-bit ARGB-poster. |
| is_compact_palette | bool | Anger om paletten är kompakt. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) och IsCompactPalette är falskt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Färgpalettens poster. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Färgpalettens poster. |
| is_compact_palette | bool | Anger om paletten är kompakt. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) och IsCompactPalette är falskt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Färgpalettens poster. |
| transparent_index | short | Det transparenta färgindexet. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Färgpalettens poster. |
| transparent_index | short | Det transparenta färgindexet. |
| use_compact_palette | bool | Anger om paletten är kompakt. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) och IsCompactPalette är falskt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raw_entries_data | byte | Råposternas data. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raw_entries_data | byte | Råposternas data. |
| is_compact_palette | bool | Anger om paletten är kompakt. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) och IsCompactPalette är falskt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raw_entries_data | byte | Råposternas data. |
| transparent_index | short | Det transparenta färgindexet. Observera att indexet inte är råposternas index utan är för den konverterade färgarrayen. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Initierar en ny instans av klassen [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raw_entries_data | byte | Råposternas data. |
| transparent_index | short | Det transparenta färgindexet. Observera att indexet inte är råposternas index utan är för den konverterade färgarrayen. |
| use_compact_palette | bool | Anger om paletten är kompakt. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Den nyss skapade och kopierade paletten eller null om en null-palett skickas. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Den nyss skapade och kopierade paletten eller null om en null-palett skickas. |


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


