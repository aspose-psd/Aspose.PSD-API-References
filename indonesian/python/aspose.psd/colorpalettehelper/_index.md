---
title: "Kelas ColorPaletteHelper"
type: docs
weight: 810
url: /id/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Membuat palet warna 4 bit. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Membuat palet skala abu-abu 4 bit. |
| [create_8_bit()](#create_8_bit__3) | Membuat palet warna 8 bit. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Membuat palet skala abu-abu 8 bit. |
| [create_monochrome()](#create_monochrome__5) | Membuat palet warna monokrom yang hanya berisi 2 warna. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Mendapatkan palet warna dari gambar raster (mem-palletkan gambar) jika gambar tidak memiliki palet. Jika palet ada, akan digunakan alih-alih melakukan perhitungan. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Mendapatkan palet warna dari gambar raster (mem-palletkan gambar) jika gambar tidak memiliki palet. Jika palet ada, akan digunakan alih-alih melakukan perhitungan. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Mendapatkan palet warna dari gambar raster (mem-palletkan gambar) jika gambar tidak memiliki palet. Jika palet ada, akan digunakan alih-alih melakukan perhitungan. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | Dapatkan palet warna 256, yang disusun dari bit atas nilai warna gambar awal. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Dapatkan palet warna 256 yang seragam. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Menentukan apakah palet yang ditentukan memiliki warna transparan. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Membuat palet warna 4 bit.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna 4 bit. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Membuat palet skala abu-abu 4 bit.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| min_is_white | bool | jika diatur ke <c>true</c> palet dimulai dengan warna putih, jika tidak dimulai dengan warna hitam. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet skala abu-abu 4 bit. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Membuat palet warna 8 bit.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna 8 bit. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Membuat palet skala abu-abu 8 bit.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| min_is_white | bool | jika diatur ke <c>true</c> palet dimulai dengan warna putih, jika tidak dimulai dengan warna hitam. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet skala abu-abu 8 bit. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Membuat palet warna monokrom yang hanya berisi 2 warna.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna untuk gambar monokrom. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Mendapatkan palet warna dari gambar raster (mem-palletkan gambar) jika gambar tidak memiliki palet. Jika palet ada, akan digunakan alih-alih melakukan perhitungan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Gambar raster. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Batas gambar tujuan. |
| entries_count | int | Jumlah entri yang diinginkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna yang dimulai dengan warna paling sering dari <paramref name="image" /> dan berisi <paramref name="entriesCount" /> entri. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Mendapatkan palet warna dari gambar raster (mem-palletkan gambar) jika gambar tidak memiliki palet. Jika palet ada, akan digunakan alih-alih melakukan perhitungan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Gambar raster. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Batas gambar tujuan. |
| entries_count | int | Jumlah entri yang diinginkan. |
| use_image_palette | bool | Jika diatur, ia akan menggunakan palet gambar miliknya jika tersedia. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna yang dimulai dengan warna paling sering dari <paramref name="image" /> dan berisi <paramref name="entriesCount" /> entri. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Mendapatkan palet warna dari gambar raster (mem-palletkan gambar) jika gambar tidak memiliki palet. Jika palet ada, akan digunakan alih-alih melakukan perhitungan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Gambar raster. |
| entries_count | int | Jumlah entri yang diinginkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna yang dimulai dengan warna paling sering dari <paramref name="image" /> dan berisi <paramref name="entriesCount" /> entri. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

Dapatkan palet warna 256, yang disusun dari bit atas nilai warna gambar awal.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Gambar. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Palet [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Dapatkan palet warna 256 yang seragam.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Gambar. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Palet [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Menentukan apakah palet yang ditentukan memiliki warna transparan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika palet yang ditentukan memiliki warna transparan; jika tidak, <c>false</c>. |


