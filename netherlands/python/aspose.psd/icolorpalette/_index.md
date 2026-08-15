---
title: "IColorPalette Klasse"
type: docs
weight: 1710
url: /nl/python-net/aspose.psd/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Haalt een array op van 32-bit ARGB-structuren. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Haalt een array op van [Color](/psd/python-net/aspose.psd/color/) structuren. |
| entries_count | int | r | Haalt het aantal vermeldingen op. |
| is_compact_palette | bool | r | Haalt een waarde op die aangeeft of een compacte palet wordt gebruikt. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Haalt de 32-bit ARGB-paletkleur op basis van index. |
| [get_color(index)](#get_color_index_2) | Haalt de paletkleur op basis van index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Haalt de index op van de dichtstbijzijnde 32-bit ARGB-kleur. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Haalt de index op van de dichtstbijzijnde 32-bit ARGB-kleur. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Haalt de index op van de dichtstbijzijnde 32-bit ARGB-kleur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb_32_color | int | De 32-bit ARGB-kleur. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De index van de dichtstbijzijnde kleur. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Haalt de index op van de dichtstbijzijnde 32-bit ARGB-kleur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De index van de dichtstbijzijnde kleur. |


