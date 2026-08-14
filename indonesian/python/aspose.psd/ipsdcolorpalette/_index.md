---
title: "Kelas IPsdColorPalette"
type: docs
weight: 1990
url: /id/python-net/aspose.psd/ipsdcolorpalette/
---

**Summary:** The pasd color palette

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPsdColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Mendapatkan array struktur ARGB 32-bit. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Mendapatkan array struktur [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Mendapatkan jumlah entri. |
| memiliki_warna_transparan | bool | r | Mendapatkan nilai yang menunjukkan apakah warna transparan ada. |
| is_compact_palette | bool | r | Mendapatkan nilai yang menunjukkan apakah palet kompak digunakan. |
| raw_entries | byte | r | Mendapatkan data entri palet warna mentah. |
| raw_entries_count | int | r | Mendapatkan jumlah entri palet warna mentah. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Mendapatkan warna transparan. |
| transparent_index | short | r | Mendapatkan indeks warna transparan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Mendapatkan warna palet ARGB 32-bit berdasarkan indeks. |
| [get_color(index)](#get_color_index_2) | Mendapatkan warna palet berdasarkan indeks. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Mendapatkan indeks warna ARGB 32-bit terdekat. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Mendapatkan indeks warna ARGB 32-bit terdekat. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

Mendapatkan warna palet ARGB 32-bit berdasarkan indeks.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks warna palet ARGB 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Entri palet warna yang ditentukan oleh <paramref name="index" />. |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

Mendapatkan warna palet berdasarkan indeks.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks warna palet. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Entri palet warna yang ditentukan oleh <paramref name="index" />. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Mendapatkan indeks warna ARGB 32-bit terdekat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb_32_color | int | Warna ARGB 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Indeks warna terdekat. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Mendapatkan indeks warna ARGB 32-bit terdekat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Indeks warna terdekat. |


