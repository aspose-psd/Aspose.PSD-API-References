---
title: "IPsdColorPalette-klass"
type: docs
weight: 1990
url: /sv/python-net/aspose.psd/ipsdcolorpalette/
---

**Summary:** The pasd color palette

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPsdColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Hämtar en matris av 32-bitars ARGB-strukturer. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Hämtar en matris av [Color](/psd/python-net/aspose.psd/color/) strukturer. |
| entries_count | int | r | Hämtar antalet poster. |
| has_transparent_color | bool | r | Hämtar ett värde som indikerar om en transparent färg finns. |
| is_compact_palette | bool | r | Hämtar ett värde som indikerar om en kompakt palett används. |
| raw_entries | byte | r | Hämtar de råa färgpalettposternas data. |
| raw_entries_count | int | r | Hämtar antalet råa färgpalettposter. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Hämtar den transparenta färgen. |
| transparent_index | short | r | Hämtar indexet för den transparenta färgen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Hämtar 32-bitars ARGB-palettfärgen efter index. |
| [get_color(index)](#get_color_index_2) | Hämtar palettfärgen efter index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Hämtar indexet för den närmaste 32-bitars ARGB-färgen. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Hämtar indexet för den närmaste 32-bitars ARGB-färgen. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Hämtar indexet för den närmaste 32-bitars ARGB-färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_color | int | Den 32-bitars ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Index för den närmaste färgen. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Hämtar indexet för den närmaste 32-bitars ARGB-färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Index för den närmaste färgen. |


