---
title: "Kelas IColorPalette"
type: docs
weight: 1710
url: /id/python-net/aspose.psd/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Mendapatkan array struktur ARGB 32-bit. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Mendapatkan array struktur [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Mendapatkan jumlah entri. |
| is_compact_palette | bool | r | Mendapatkan nilai yang menunjukkan apakah palet kompak digunakan. |
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


