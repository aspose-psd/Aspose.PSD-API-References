---
title: "Kelas RawColor"
type: docs
weight: 20
url: /id/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Menginisialisasi instance baru dari kelas [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) . |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Menginisialisasi instance baru dari kelas [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) dari format data piksel menggunakan mode warna yang telah ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Mode untuk warna yang akan diikuti. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Mendapatkan komponen warna. Setiap komponen adalah saluran terpisah, dan jika Anda menggunakan skema warna yang tidak populer<br/>            lebih baik bekerja dengan setiap saluran secara terpisah. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Mendapatkan warna sebagai int jika memungkinkan. |
| [get_as_long()](#get_as_long__2) | Mendapatkan warna sebagai long jika memungkinkan. |
| [get_bit_depth()](#get_bit_depth__3) | Mendapatkan kedalaman bit dari Raw Color. <br/>            Misalnya untuk warna ARGB dengan 8 bit per saluran/komponen adalah 32<br/>            Kedalaman Bit dari warna ARGB penuh dengan 16 bit per saluran/komponen adalah 64.<br/>            Kedalaman bit diakumulasi dari jumlah kedalaman bit masing-masing saluran. <br/>            Hal ini memungkinkan jika saluran yang berbeda memiliki kedalaman bit yang berbeda. |
| [get_color_mode_name()](#get_color_mode_name__4) | Mendapatkan nama mode warna. Nama mode warna diakumulasi dari nama saluran/komponen. |
| [set_as_int(value)](#set_as_int_value_5) | Mengatur data ke semua saluran dari argumen int jika memungkinkan. |
| [set_as_long(value)](#set_as_long_value_6) | Mengatur data ke semua saluran dari argumen int jika memungkinkan. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Menginisialisasi instance baru dari kelas [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | Komponen warna kustom. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Menginisialisasi instance baru dari kelas [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) dari format data piksel menggunakan mode warna yang telah ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Format data piksel. |
| color_mode | short | Mode untuk warna yang akan diikuti. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Mendapatkan warna sebagai int jika memungkinkan.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Data saluran disimpan dalam Int. |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Mendapatkan warna sebagai long jika memungkinkan.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| long | Data saluran disimpan dalam Int. |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Mendapatkan kedalaman bit dari Raw Color. <br/>            Misalnya untuk warna ARGB dengan 8 bit per saluran/komponen adalah 32<br/>            Kedalaman Bit dari warna ARGB penuh dengan 16 bit per saluran/komponen adalah 64.<br/>            Kedalaman bit diakumulasi dari jumlah kedalaman bit masing-masing saluran. <br/>            Hal ini memungkinkan jika saluran yang berbeda memiliki kedalaman bit yang berbeda.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Jumlah kedalaman bit semua saluran. |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Mendapatkan nama mode warna. Nama mode warna diakumulasi dari nama saluran/komponen.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | String dengan nama mode warna. |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Mengatur data ke semua saluran dari argumen int jika memungkinkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | int | Nilai int yang berisi data komponen. |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Mengatur data ke semua saluran dari argumen int jika memungkinkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | long | Nilai int yang berisi data komponen. |

