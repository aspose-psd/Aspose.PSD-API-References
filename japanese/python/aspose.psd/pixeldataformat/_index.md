---
title: "PixelDataFormat クラス"
type: docs
weight: 3450
url: /ja/python-net/aspose.psd/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PixelDataFormat

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r | 1ピクセルあたりのビット数を取得します。 |
| キャプション | string | r | ピクセルデータ形式のキャプションを取得します。 |
| channel_bits | int | r | 各チャンネルのビット数を取得します。 |
| channels_count | int | r | チャンネル数を取得します。 |
| cmyk [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 32ビット/ピクセルで、シアン、マゼンタ、イエロー、ブラックそれぞれに8ビットが割り当てられた [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) を取得します。 |
| cmyka [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | acmyk を取得します。 |
| grayscale [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 0〜255 の範囲でグレースケール強度を表す8ビットを持つ、8ビット/ピクセルの [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) を取得します。 |
| grayscale_alpha [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 0〜255 の範囲でグレースケール強度を表す8ビットに加えて、8ビットのアルファ成分を持つ、16ビット/ピクセルの [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) を取得します。 |
| pixel_format | [PixelFormat](/psd/python-net/aspose.psd/pixelformat) | r | ピクセル形式を取得します。 |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 赤、緑、青それぞれに5ビットが割り当てられ、アルファは未定義の16ビット/ピクセルの [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) を取得します。 |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 赤5ビット、緑6ビット、青5ビットが割り当てられ、アルファは未定義の16ビット/ピクセルの [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) を取得します。 |
| rgb_24_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | アルファ、赤、緑、青それぞれに8ビットが割り当てられ、アルファは未定義の24ビット/ピクセルの [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) を取得します。 |
| rgb_24_bpp_png [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | アルファ、赤、緑、青それぞれに8ビットが割り当てられ、アルファは未定義の24ビット/ピクセルの [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) を取得します。 |
| rgb_32_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | アルファ、赤、緑、青それぞれに8ビットが割り当てられた32ビット/ピクセルの [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) を取得します。 |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | インデックス化された1ビット/カラーの [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) を取得します。<br/>            インデックスピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを目的としています。<br/>            注意して使用してください。パレット間の変換や RGBA からインデックスカラー形式への変換が必要になる可能性があります。 |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 取得します [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) は、インデックスされた 2 ビット/カラー用に定義されています。<br/>            インデックスされたピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを目的としています。<br/>            注意して使用してください。パレット間または RGBA からインデックスカラーへの変換が必要になる場合があります。 |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 取得します [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) は、インデックスされた 4 ビット/カラー用に定義されています。<br/>            インデックスされたピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを目的としています。<br/>            注意して使用してください。パレット間または RGBA からインデックスカラーへの変換が必要になる場合があります。 |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 取得します [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) は、インデックスされた 8 ビット/カラー用に定義されています。<br/>            インデックスされたピクセルデータの保存は、カラーパレットが使用されるすべての場所でデータの保存と取得を可能にすることを目的としています。<br/>            注意して使用してください。パレット間または RGBA からインデックスカラーへの変換が必要になる場合があります。 |
| rgba_32_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | アルファ、赤、緑、青それぞれに8ビットが割り当てられた32ビット/ピクセルの [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) を取得します。 |
| rgba_64_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 取得します [PixelDataFormat] は、アルファ、赤、緑、青それぞれ 16 ビットで、1 ピクセルあたり 64 ビットで定義されています。 |
| y_cb_cr [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 取得します [PixelDataFormat] は、ルーマ、青差、赤差のクロマ成分それぞれ 8 ビットで、1 ピクセルあたり 24 ビットで定義されています。 |
| ycck [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 取得します [PixelDataFormat] は、ルーマ、青差、赤差、黒のクロマ成分それぞれ 8 ビットで、1 ピクセルあたり 32 ビットで定義されています。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | 指定されたサンプルあたりのビット数で BGRA カラーを取得します。 |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | 指定されたサンプルあたりのビット数で BGRA カラーを取得します。 |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | 指定されたサンプルあたりのビット数で CIE Lab カラーを取得します。 |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | 指定されたサンプルあたりのビット数で CMYK カラーを取得します。 |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | 指定されたサンプルあたりのビット数で CMYK カラーを取得します。 |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | 指定されたサンプルあたりのビット数で CMYKA カラーを取得します。 |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | 指定されたサンプルあたりのビット数でグレースケールカラーを取得します。 |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | 指定されたサンプルあたりのビット数でグレースケールアルファカラーを取得します。 |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | 指定されたサンプルあたりのビット数でグレースケールアルファカラーを取得します。 |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | 指定されたサンプルあたりのビット数で RGB カラーを取得します。 |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | 指定されたサンプルあたりのビット数で RGB カラーを取得します。 |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | 指定されたサンプルあたりのビット数で BGRA インデックスカラーを取得します。 |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | 指定されたサンプルあたりのビット数で RGBA カラーを取得します。 |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | 指定されたサンプルあたりのビット数で RGBA カラーを取得します。 |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | 指定されたサンプルあたりのビット数で YCbCr カラーを取得します。 |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | 指定されたサンプルあたりのビット数で YCbCr カラーを取得します。 |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | 指定されたサンプルあたりのビット数で YCCK カラーを取得します。 |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

指定されたサンプルあたりのビット数で BGRA カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA カラーです。 |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

指定されたサンプルあたりのビット数で BGRA カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA カラーです。 |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

指定されたサンプルあたりのビット数で CIE Lab カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_l | int | L チャネルあたりのビット数です。 |
| bits_per_a | int | A チャネルあたりのビット数です。 |
| bits_per_b | int | B チャネルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CIE Lab カラーです。 |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

指定されたサンプルあたりのビット数で CMYK カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_cyan_channel | int | Cyan チャネルあたりのビット数です。 |
| bits_per_magenta_channel | int | Magenta チャネルあたりのビット数です。 |
| bits_per_yellow_channel | int | Yellow チャネルあたりのビット数です。 |
| bits_per_key_channel | int | Key チャネルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK カラーです。 |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

指定されたサンプルあたりのビット数で CMYK カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK カラーです。 |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

指定されたサンプルあたりのビット数で CMYKA カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_cyan_channel | int | Cyan チャネルあたりのビット数です。 |
| bits_per_magenta_channel | int | Magenta チャネルあたりのビット数です。 |
| bits_per_yellow_channel | int | Yellow チャネルあたりのビット数です。 |
| bits_per_key_channel | int | Key チャネルあたりのビット数です。 |
| bits_per_alpha_channel | int | Alpha チャネルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK カラーです。 |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

指定されたサンプルあたりのビット数でグレースケールカラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Grayscale カラーです。 |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

指定されたサンプルあたりのビット数でグレースケールアルファカラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | GrayscaleAlpha カラーです。 |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

指定されたサンプルあたりのビット数でグレースケールアルファカラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |
| alpha_channel_bits | int | アルファチャネル内のサンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | GrayscaleAlpha カラーです。 |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

指定されたサンプルあたりのビット数で RGB カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_red_channel | int | Red チャネルあたりのビット数です。 |
| bits_per_green_channel | int | Green チャネルあたりのビット数です。 |
| bits_per_blue_channel | int | Blue チャネルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGB カラーです。 |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

指定されたサンプルあたりのビット数で RGB カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGB カラーです。 |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

指定されたサンプルあたりのビット数で BGRA インデックスカラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA カラーです。 |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

指定されたサンプルあたりのビット数で RGBA カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_red_channel | int | Red チャネルあたりのビット数です。 |
| bits_per_green_channel | int | Green チャネルあたりのビット数です。 |
| bits_per_blue_channel | int | Blue チャネルあたりのビット数です。 |
| bits_per_alpha_channel | int | Alpha チャネルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGBA カラーです。 |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

指定されたサンプルあたりのビット数で RGBA カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGBA カラーです。 |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

指定されたサンプルあたりのビット数で YCbCr カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCbCr カラーです。 |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

指定されたサンプルあたりのビット数で YCbCr カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_y | int | Yチャンネルあたりのビット数。 |
| bits_per_cb | int | Cbチャンネルあたりのビット数。 |
| bits_per_cr | int | Crチャンネルあたりのビット数。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCbCr カラーです。 |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

指定されたサンプルあたりのビット数で YCCK カラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bits_per_sample | int | サンプルあたりのビット数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCCKカラー。 |


