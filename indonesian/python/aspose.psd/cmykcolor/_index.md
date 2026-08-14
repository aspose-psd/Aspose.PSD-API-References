---
title: "Kelas CmykColor"
type: docs
weight: 630
url: /id/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Menginisialisasi instance baru dari kelas CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| c | byte | r | Mendapatkan nilai komponen sian dari struktur [Color](/psd/python-net/aspose.psd/color/) ini. |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Mendapatkan nilai kosong. |
| is_empty | bool | r | Mendapatkan nilai yang menunjukkan apakah struktur [Color](/psd/python-net/aspose.psd/color/) ini belum diinisialisasi. |
| k | byte | r | Mendapatkan nilai komponen hitam dari struktur [Color](/psd/python-net/aspose.psd/color/) ini. |
| m | byte | r | Mendapatkan nilai komponen magenta dari struktur [Color](/psd/python-net/aspose.psd/color/) ini. |
| y | byte | r | Mendapatkan nilai komponen kuning dari struktur [Color](/psd/python-net/aspose.psd/color/) ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Membuat struktur [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) dari nilai 32-bit sian, magenta, kuning, dan hitam.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | Konversi dari CMYKColor ke Warna ARGB 32-bit menggunakan konversi icc dengan profil default.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | Konversi dari warna ARGB 32-bit ke CMYKColor.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | Konversi dari warna ARGB 32-bit ke CMYKColor.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | Konversi dari CMYKColor ke Color menggunakan konversi icc.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | Konversi dari CMYKColor ke Color menggunakan konversi icc.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_value()](#to_value__11) | Nilai to. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Menginisialisasi instance baru dari kelas CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Membuat struktur [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) dari nilai 32-bit sian, magenta, kuning, dan hitam.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sian | int | Komponen cyan. Nilai yang valid adalah 0 hingga 255. |
| magenta | int | Komponen magenta. Nilai yang valid adalah 0 hingga 255. |
| kuning | int | Komponen kuning. Nilai yang valid adalah 0 hingga 255. |
| hitam | int | Komponen hitam. Nilai yang valid adalah 0 hingga 255. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Objek [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

Konversi dari CMYKColor ke Warna ARGB 32-bit menggunakan konversi icc dengan profil default.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Piksel tipe CMYKColor dalam format CMYK. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Array dari warna ARGB 32-bit. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

Konversi dari warna ARGB 32-bit ke CMYKColor.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Elemen <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

Konversi dari warna ARGB 32-bit ke CMYKColor.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb_pixels | int | Piksel dalam format ARGB 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Elemen <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Array dari warna ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Piksel tipe CMYKColor dalam format CMYK. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Array dari warna ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Array [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Konversi dari CMYKColor ke Color menggunakan konversi icc.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | Aliran yang berisi profil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Aliran yang berisi profil icc rgb. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Array [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Piksel tipe CMYKColor dalam format CMYK. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Array [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Konversi dari CMYKColor ke Color menggunakan konversi icc.<br/>            Metode ini sudah usang. Silakan gunakan yang lebih efektif Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Piksel tipe CMYKColor dalam format CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Aliran yang berisi profil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Aliran yang berisi profil icc rgb. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Array [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

Nilai to.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| long | Bilangan bulat. |


