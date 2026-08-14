---
title: "IColorPalette Klasse"
type: docs
weight: 1710
url: /de/python-net/aspose.psd/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Gibt ein Array von 32-bit ARGB Strukturen zurück. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Gibt ein Array von [Color](/psd/python-net/aspose.psd/color/) Strukturen zurück. |
| entries_count | int | r | Gibt die Anzahl der Einträge zurück. |
| is_compact_palette | bool | r | Gibt einen Wert zurück, der angibt, ob eine kompakte Palette verwendet wird. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Gibt die 32-bit ARGB Palettenfarbe nach Index zurück. |
| [get_color(index)](#get_color_index_2) | Gibt die Palettenfarbe nach Index zurück. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Gibt den Index der nächstgelegenen 32-bit ARGB Farbe zurück. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Gibt den Index der nächstgelegenen 32-bit ARGB Farbe zurück. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Gibt den Index der nächstgelegenen 32-bit ARGB Farbe zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_32_color | int | Die 32‑Bit‑ARGB‑Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Index der nächsten Farbe. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Gibt den Index der nächstgelegenen 32-bit ARGB Farbe zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Index der nächsten Farbe. |


