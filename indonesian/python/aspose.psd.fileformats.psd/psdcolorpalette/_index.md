---
title: "Kelas PsdColorPalette"
type: docs
weight: 1750
url: /id/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) dan IsCompactPalette adalah false. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) dan IsCompactPalette adalah false. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) dan IsCompactPalette adalah false. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) dan IsCompactPalette adalah false. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Mendapatkan array warna ARGB 32-bit. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Mendapatkan array struktur [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Mendapatkan jumlah entri. |
| memiliki_warna_transparan | bool | r | Mendapatkan nilai yang menunjukkan apakah warna transparan ada. |
| is_compact_palette | bool | r | Mendapatkan nilai yang menunjukkan apakah paletnya kompak. |
| raw_entries | byte | r | Mendapatkan data entri palet warna mentah. |
| raw_entries_count | int | r | Mendapatkan jumlah entri palet warna mentah. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Mendapatkan warna transparan. |
| transparent_index | short | r | Mendapatkan indeks warna transparan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Menyalin palet. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Menyalin palet. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Mendapatkan warna palet ARGB 32-bit berdasarkan indeks. |
| [get_color(index)](#get_color_index_4) | Mendapatkan warna palet berdasarkan indeks. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Mendapatkan indeks warna terdekat. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Mendapatkan indeks warna terdekat. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna. |
| transparent_index | short | Indeks warna transparan. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_palette_argb_32_entries | int | Entri palet warna 32-bit ARGB. |
| is_compact_palette | bool | Menunjukkan apakah palet tersebut kompak. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) dan IsCompactPalette adalah false.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Entri palet warna. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Entri palet warna. |
| is_compact_palette | bool | Menunjukkan apakah palet tersebut kompak. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) dan IsCompactPalette adalah false.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Entri palet warna. |
| transparent_index | short | Indeks warna transparan. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Entri palet warna. |
| transparent_index | short | Indeks warna transparan. |
| use_compact_palette | bool | Menunjukkan apakah palet tersebut kompak. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) dan IsCompactPalette adalah false.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| raw_entries_data | byte | Data entri mentah. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| raw_entries_data | byte | Data entri mentah. |
| is_compact_palette | bool | Menunjukkan apakah palet tersebut kompak. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) dan IsCompactPalette adalah false.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| raw_entries_data | byte | Data entri mentah. |
| transparent_index | short | Indeks warna transparan. Catatan indeks bukan indeks entri mentah melainkan untuk array warna yang dikonversi. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Menginisialisasi instansi baru dari kelas [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| raw_entries_data | byte | Data entri mentah. |
| transparent_index | short | Indeks warna transparan. Catatan indeks bukan indeks entri mentah melainkan untuk array warna yang dikonversi. |
| use_compact_palette | bool | Menunjukkan apakah palet tersebut kompak. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Palet yang baru dibuat dan disalin atau null jika palet null diberikan. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Palet yang baru dibuat dan disalin atau null jika palet null diberikan. |


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


