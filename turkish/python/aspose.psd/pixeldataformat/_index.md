---
title: "PixelDataFormat Sınıfı"
type: docs
weight: 3450
url: /tr/python-net/aspose.psd/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PixelDataFormat

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r | Piksel başına bit sayısını alır. |
| başlık | string | r | Piksel veri formatı başlığını alır. |
| channel_bits | int | r | Her kanal için bit sayısını alır. |
| channels_count | int | r | Kanal sayısını alır. |
| cmyk [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 32 bit piksel başına, camgöbeği, macenta, sarı ve siyah için her biri 8 bit olan [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) tanımını alır. |
| cmyka [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | acmyk değerini alır. |
| grayscale [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ile piksel başına 8 bit tanımlı [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır. |
| grayscale_alpha [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ve ek 8 bit alfa bileşeni ile piksel başına 16 bit tanımlı [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır. |
| pixel_format | [PixelFormat](/psd/python-net/aspose.psd/pixelformat) | r | Piksel formatını alır. |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Kırmızı, yeşil ve mavi için her biri 5 bit ve alfa tanımlanmamış olmak üzere piksel başına 16 bit tanımlı [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır. |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Kırmızı için 5 bit, yeşil için 6 bit ve mavi için 5 bit, alfa tanımlanmamış olmak üzere piksel başına 16 bit tanımlı [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır. |
| rgb_24_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Alfa, kırmızı, yeşil ve mavi için her biri 8 bit ve alfa tanımlanmamış olmak üzere piksel başına 24 bit tanımlı [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır. |
| rgb_24_bpp_png [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Alfa, kırmızı, yeşil ve mavi için her biri 8 bit ve alfa tanımlanmamış olmak üzere piksel başına 24 bit tanımlı [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır. |
| rgb_32_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Alfa, kırmızı, yeşil ve mavi için her biri 8 bit olmak üzere piksel başına 32 bit tanımlı [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır. |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Renk başına indeksli 1 bit tanımlı [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır.<br/>            İndeksli piksel veri depolaması, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak amacıyla tasarlanmıştır.<br/>            Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Belirtilen renk başına 2 bit indeksli için tanımlanan [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır.<br/>            İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak amacıyla tasarlanmıştır.<br/>            Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Belirtilen renk başına 4 bit indeksli için tanımlanan [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır.<br/>            İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak amacıyla tasarlanmıştır.<br/>            Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Belirtilen renk başına 8 bit indeksli için tanımlanan [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır.<br/>            İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak amacıyla tasarlanmıştır.<br/>            Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| rgba_32_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Alfa, kırmızı, yeşil ve mavi için her biri 8 bit olmak üzere piksel başına 32 bit tanımlı [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) alır. |
| rgba_64_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Piksel başına 64 bit, alfa, kırmızı, yeşil ve mavi için her biri 16 bit tanımlanan [PixelDataFormat] alır. |
| y_cb_cr [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Piksel başına 24 bit, luma, mavi-fark ve kırmızı-fark renk doygunluk bileşenleri için her biri 8 bit tanımlanan [PixelDataFormat] alır. |
| ycck [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Piksel başına 32 bit, luma, mavi-fark, kırmızı-fark ve siyah renk doygunluk bileşenleri için her biri 8 bit tanımlanan [PixelDataFormat] alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | Belirtilen örnek başına bit sayısıyla BGRA rengini alır. |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | Belirtilen örnek başına bit sayısıyla BGRA rengini alır. |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | Belirtilen örnek başına bit sayısıyla CIE Lab rengini alır. |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | Belirtilen örnek başına bit sayısıyla CMYK rengini alır. |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | Belirtilen örnek başına bit sayısıyla CMYK rengini alır. |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | Belirtilen örnek başına bit sayısıyla CMYKA rengini alır. |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | Belirtilen örnek başına bit sayısıyla Gri tonlamalı rengi alır. |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | Belirtilen örnek başına bit sayısıyla Gri tonlamalı Alfa rengini alır. |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | Belirtilen örnek başına bit sayısıyla Gri tonlamalı Alfa rengini alır. |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | Belirtilen örnek başına bit sayısıyla RGB rengini alır. |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | Belirtilen örnek başına bit sayısıyla RGB rengini alır. |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | Belirtilen örnek başına bit sayısıyla BGRA indeksli rengini alır. |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | Belirtilen örnek başına bit sayısıyla RGBA rengini alır. |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | Belirtilen örnek başına bit sayısıyla RGBA rengini alır. |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | Belirtilen örnek başına bit sayısıyla YCbCr rengini alır. |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | Belirtilen örnek başına bit sayısıyla YCbCr rengini alır. |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | Belirtilen örnek başına bit sayısıyla YCCK rengini alır. |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

Belirtilen örnek başına bit sayısıyla BGRA rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA rengi. |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

Belirtilen örnek başına bit sayısıyla BGRA rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA rengi. |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

Belirtilen örnek başına bit sayısıyla CIE Lab rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_l | int | L kanalı başına bit sayısı. |
| bits_per_a | int | A kanalı başına bit sayısı. |
| bits_per_b | int | B kanalı başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | The CIE Lab rengi. |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

Belirtilen örnek başına bit sayısıyla CMYK rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_cyan_channel | int | Cyan kanal başına bit sayısı. |
| bits_per_magenta_channel | int | Magenta kanal başına bit sayısı. |
| bits_per_yellow_channel | int | Yellow kanal başına bit sayısı. |
| bits_per_key_channel | int | Key kanal başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK rengi. |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

Belirtilen örnek başına bit sayısıyla CMYK rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK rengi. |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

Belirtilen örnek başına bit sayısıyla CMYKA rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_cyan_channel | int | Cyan kanal başına bit sayısı. |
| bits_per_magenta_channel | int | Magenta kanal başına bit sayısı. |
| bits_per_yellow_channel | int | Yellow kanal başına bit sayısı. |
| bits_per_key_channel | int | Key kanal başına bit sayısı. |
| bits_per_alpha_channel | int | Alpha kanal başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK rengi. |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

Belirtilen örnek başına bit sayısıyla Gri tonlamalı rengi alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Gri tonlamalı renk. |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

Belirtilen örnek başına bit sayısıyla Gri tonlamalı Alfa rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | GrayscaleAlpha rengi. |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

Belirtilen örnek başına bit sayısıyla Gri tonlamalı Alfa rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |
| alpha_channel_bits | int | Alfa kanalındaki örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | GrayscaleAlpha rengi. |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

Belirtilen örnek başına bit sayısıyla RGB rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_red_channel | int | Red kanal başına bit sayısı. |
| bits_per_green_channel | int | Green kanal başına bit sayısı. |
| bits_per_blue_channel | int | Blue kanal başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGB rengi. |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

Belirtilen örnek başına bit sayısıyla RGB rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGB rengi. |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

Belirtilen örnek başına bit sayısıyla BGRA indeksli rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA rengi. |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

Belirtilen örnek başına bit sayısıyla RGBA rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_red_channel | int | Red kanal başına bit sayısı. |
| bits_per_green_channel | int | Green kanal başına bit sayısı. |
| bits_per_blue_channel | int | Blue kanal başına bit sayısı. |
| bits_per_alpha_channel | int | Alpha kanal başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGBA rengi. |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

Belirtilen örnek başına bit sayısıyla RGBA rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGBA rengi. |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

Belirtilen örnek başına bit sayısıyla YCbCr rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCbCr rengi. |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

Belirtilen örnek başına bit sayısıyla YCbCr rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_y | int | Y kanalındaki bit sayısı. |
| bits_per_cb | int | Cb kanalındaki bit sayısı. |
| bits_per_cr | int | Cr kanalındaki bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCbCr rengi. |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

Belirtilen örnek başına bit sayısıyla YCCK rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bits_per_sample | int | Örnek başına bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCCK rengi. |


