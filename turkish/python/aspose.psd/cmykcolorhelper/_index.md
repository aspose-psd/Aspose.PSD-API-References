---
title: "CmykColorHelper Sınıfı"
type: docs
weight: 640
url: /tr/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | 32-bit cyan, magenta, yellow ve black değerlerinden CMYK oluşturur. |
| [get_c(cmyk)](#get_c_cmyk_2) | Cyan bileşen değerini alır. |
| [get_k(cmyk)](#get_k_cmyk_3) | Siyah bileşen değerini alır. |
| [get_m(cmyk)](#get_m_cmyk_4) | Magenta bileşen değerini alır. |
| [get_y(cmyk)](#get_y_cmyk_5) | Sarı bileşen değerini alır. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | CMYK renklerinden ARGB renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | Özel profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | CMYK renklerinden ARGB renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | Özel profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | RGB'yi CMYK'ye dönüştürür. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Özel ICC profilleri kullanarak RGB'yi CMYK'ye dönüştürür. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

32-bit cyan, magenta, yellow ve black değerlerinden CMYK oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| camgöbeği | int | Camgöbeği bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| macenta | int | Macenta bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| sarı | int | Sarı bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| siyah | int | Siyah bileşeni. Geçerli değerler 0 ile 255 arasındadır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Cyan bileşen değerini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Camgöbeği bileşen değeri. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Siyah bileşen değerini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Siyah bileşen değeri. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Magenta bileşen değerini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Macenta bileşen değeri. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Sarı bileşen değerini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Sarı bileşen değeri. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB renkleri. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB renkleri. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | ARGB renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

CMYK renklerinden ARGB renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB renkleri. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB renkleri. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

CMYK renklerinden ARGB renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int | CMYK pikselleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB renkleri. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB renkleri. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb_pixels | int | ARGB renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

RGB'yi CMYK'ye dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb_pixels | int | 32 bit tamsayı değerleri olarak sunulan RGB renkleri. |
| start_index | int | RGB renginin başlangıç indeksi. |
| uzunluk | int | Dönüştürülecek RGB piksel sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Bayt dizisi olarak sunulan CMYK renkleri. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB renkleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB renkleri. |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc profilini içeren akış. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Özel ICC profilleri kullanarak RGB'yi CMYK'ye dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| piksel | int | 32 bit tamsayı değerleri olarak sunulan RGB renkleri. |
| start_index | int | RGB renginin başlangıç indeksi. |
| uzunluk | int | Dönüştürülecek RGB piksel sayısı. |
| rgb_icc_stream | _io.BufferedRandom | RGB profil akışı. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK profil akışı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Bayt dizisi olarak sunulan CMYK renkleri. |


