---
title: "Kelas ColorPalette"
type: docs
weight: 800
url: /id/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Menginisialisasi sebuah instance baru dari kelas [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) dan IsCompactPalette bernilai false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Menginisialisasi sebuah instance baru dari kelas [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Menginisialisasi sebuah instance baru dari kelas [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) dan IsCompactPalette bernilai false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Menginisialisasi sebuah instance baru dari kelas [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Mendapatkan array struktur ARGB 32-bit. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Mendapatkan array struktur [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Mendapatkan jumlah entri. |
| is_compact_palette | bool | r | Mendapatkan atau mengatur nilai yang menunjukkan apakah palet kompak digunakan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Menyalin palet. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Menyalin palet. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Mendapatkan warna palet ARGB 32-bit berdasarkan indeks. |
| [get_color(index)](#get_color_index_4) | Mendapatkan warna palet berdasarkan indeks. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Mendapatkan indeks warna terdekat. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Mendapatkan indeks warna terdekat. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Menginisialisasi sebuah instance baru dari kelas [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) dan IsCompactPalette bernilai false.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb_32_entries | int | Entri palet warna ARGB 32-bit. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Menginisialisasi sebuah instance baru dari kelas [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb_32_entries | int | Entri palet warna ARGB 32-bit. |
| is_compact_palette | bool | Menunjukkan apakah palet tersebut kompak. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Menginisialisasi sebuah instance baru dari kelas [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) dan IsCompactPalette bernilai false.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Menginisialisasi sebuah instance baru dari kelas [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Menunjukkan apakah palet tersebut kompak. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Menyalin palet.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Palet yang baru dibuat dan disalin atau null jika palet null diberikan. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Menyalin palet.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna. |
| use_compact_palette | bool | Menunjukkan apakah palet kompak. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Palet yang baru dibuat dan disalin atau null jika palet null diberikan. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


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


### Method: get_color(index) {#get_color_index_4}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

Mendapatkan indeks warna terdekat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb_32_color | int | Warna ARGB 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Indeks warna terdekat. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

Mendapatkan indeks warna terdekat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Indeks warna terdekat. |


