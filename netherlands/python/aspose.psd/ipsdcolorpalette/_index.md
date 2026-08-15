---
title: "IPsdColorPalette Klasse"
type: docs
weight: 1990
url: /nl/python-net/aspose.psd/ipsdcolorpalette/
---

**Summary:** The pasd color palette

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPsdColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Haalt een array op van 32-bit ARGB-structuren. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Haalt een array op van [Color](/psd/python-net/aspose.psd/color/) structuren. |
| entries_count | int | r | Haalt het aantal vermeldingen op. |
| has_transparent_color | bool | r | Haalt een waarde op die aangeeft of er een transparante kleur bestaat. |
| is_compact_palette | bool | r | Haalt een waarde op die aangeeft of een compacte palet wordt gebruikt. |
| raw_entries | byte | r | Haalt de ruwe gegevens van de kleurpaletvermeldingen op. |
| raw_entries_count | int | r | Haalt het aantal ruwe kleurpaletvermeldingen op. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Haalt de transparante kleur op. |
| transparent_index | short | r | Haalt de index van de transparante kleur op. |
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


