---
title: "IColorPalette Sınıfı"
type: docs
weight: 1710
url: /tr/python-net/aspose.psd/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32-bit ARGB yapıların bir dizisini alır. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | [Color](/psd/python-net/aspose.psd/color/) yapıların bir dizisini alır. |
| entries_count | int | r | Giriş sayısını alır. |
| is_compact_palette | bool | r | Kompakt paletin kullanılıp kullanılmadığını gösteren bir değeri alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | İndeks ile 32-bit ARGB palet rengini alır. |
| [get_color(index)](#get_color_index_2) | İndeks ile palet rengini alır. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | En yakın 32-bit ARGB renginin indeksini alır. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | En yakın 32-bit ARGB renginin indeksini alır. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

İndeks ile 32-bit ARGB palet rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| indeks | int | 32-bit ARGB palet renk indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | <paramref name="index" /> tarafından belirtilen renk paleti girdisi. |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

İndeks ile palet rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| indeks | int | Palet renk indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | <paramref name="index" /> tarafından belirtilen renk paleti girdisi. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

En yakın 32-bit ARGB renginin indeksini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb_32_color | int | 32-bit ARGB rengi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | En yakın rengin indeksi. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

En yakın 32-bit ARGB renginin indeksini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | En yakın rengin indeksi. |


