---
title: "Kelas CmykColorHelper"
type: docs
weight: 640
url: /id/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | Membuat CMYK dari nilai cyan, magenta, kuning, dan hitam 32-bit. |
| [get_c(cmyk)](#get_c_cmyk_2) | Mendapatkan nilai komponen cyan. |
| [get_k(cmyk)](#get_k_cmyk_3) | Mendapatkan nilai komponen hitam. |
| [get_m(cmyk)](#get_m_cmyk_4) | Mendapatkan nilai komponen magenta. |
| [get_y(cmyk)](#get_y_cmyk_5) | Mendapatkan nilai komponen kuning. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | Konversi dari warna CMYK ke warna ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | Konversi dari warna CMYK ke warna ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | Konversi dari warna CMYK ke warna ARGB. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil default. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil khusus. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil default. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil khusus. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | Konversi dari warna ARGB ke warna CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | Konversi dari warna ARGB ke warna CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | Konversi dari warna ARGB ke warna CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | Konversi dari warna ARGB ke warna CMYK. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | Mengonversi RGB ke CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil default. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil khusus. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil default. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil khusus. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Mengonversi RGB ke CMYK menggunakan profil ICC khusus. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

Membuat CMYK dari nilai cyan, magenta, kuning, dan hitam 32-bit.

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
| int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Mendapatkan nilai komponen cyan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Nilai komponen cyan. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Mendapatkan nilai komponen hitam.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Nilai komponen hitam. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Mendapatkan nilai komponen magenta.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Nilai komponen magenta. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Mendapatkan nilai komponen kuning.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Nilai komponen kuning. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

Konversi dari warna CMYK ke warna ARGB.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Warna ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

Konversi dari warna CMYK ke warna ARGB.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixels | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Warna ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

Konversi dari warna CMYK ke warna ARGB.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixels | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Warna ARGB yang disajikan sebagai nilai integer 32-bit. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Warna ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil khusus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Aliran yang berisi profil Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Aliran yang berisi profil Icc RGB. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Warna ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixels | int | Piksel CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Warna ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil khusus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cmyk_pixels | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |
| cmyk_icc_stream | _io.BufferedRandom | Aliran yang berisi profil Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Aliran yang berisi profil Icc RGB. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Warna ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

Konversi dari warna ARGB ke warna CMYK.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

Konversi dari warna ARGB ke warna CMYK.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb_pixels | int | Warna ARGB yang disajikan sebagai nilai integer 32-bit. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

Konversi dari warna ARGB ke warna CMYK.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

Konversi dari warna ARGB ke warna CMYK.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Mengonversi RGB ke CMYK.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb_pixels | int | Warna RGB yang disajikan sebagai nilai integer 32-bit. |
| start_index | int | Indeks mulai warna RGB. |
| panjang | int | Jumlah piksel RGB yang akan dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Warna CMYK yang disajikan sebagai array byte. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil khusus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | Aliran yang berisi profil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Aliran yang berisi profil Icc CMYK. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Warna ARGB. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil khusus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Warna ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Aliran yang berisi profil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Aliran yang berisi profil Icc CMYK. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Mengonversi RGB ke CMYK menggunakan profil ICC khusus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pixels | int | Warna RGB yang disajikan sebagai nilai integer 32-bit. |
| start_index | int | Indeks mulai warna RGB. |
| panjang | int | Jumlah piksel RGB yang akan dikonversi. |
| rgb_icc_stream | _io.BufferedRandom | Aliran profil RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Aliran profil CMYK. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Warna CMYK yang disajikan sebagai array byte. |


