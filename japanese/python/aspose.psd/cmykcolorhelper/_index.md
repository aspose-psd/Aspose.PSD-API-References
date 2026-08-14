---
title: "CmykColorHelper クラス"
type: docs
weight: 640
url: /ja/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | 32ビットのシアン、マゼンタ、イエロー、ブラック値から CMYK を作成します。 |
| [get_c(cmyk)](#get_c_cmyk_2) | シアン成分の値を取得します。 |
| [get_k(cmyk)](#get_k_cmyk_3) | ブラック成分の値を取得します。 |
| [get_m(cmyk)](#get_m_cmyk_4) | マゼンタ成分の値を取得します。 |
| [get_y(cmyk)](#get_y_cmyk_5) | イエロー成分の値を取得します。 |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | CMYK カラーから ARGB カラーへの変換。 |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | CMYK カラーから ARGB カラーへの変換。 |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | CMYK カラーから ARGB カラーへの変換。 |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | デフォルトプロファイルを使用した ICC 変換により、CMYK カラーから ARGB カラーへの変換。 |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | CMYK カラーから ARGB カラーへの変換（カスタムプロファイルを使用した Icc 変換）。 |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | デフォルトプロファイルを使用した ICC 変換により、CMYK カラーから ARGB カラーへの変換。 |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | CMYK カラーから ARGB カラーへの変換（カスタムプロファイルを使用した Icc 変換）。 |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | ARGB カラーから CMYK カラーへの変換。 |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | ARGB カラーから CMYK カラーへの変換。 |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | ARGB カラーから CMYK カラーへの変換。 |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | ARGB カラーから CMYK カラーへの変換。 |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | RGB を CMYK に変換します。 |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | ARGB カラーから CMYK カラーへの変換（デフォルトプロファイルを使用した Icc 変換）。 |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | ARGB カラーから CMYK カラーへの変換（カスタムプロファイルを使用した Icc 変換）。 |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | ARGB カラーから CMYK カラーへの変換（デフォルトプロファイルを使用した Icc 変換）。 |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | ARGB カラーから CMYK カラーへの変換（カスタムプロファイルを使用した Icc 変換）。 |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | カスタム ICC プロファイルを使用して RGB を CMYK に変換します。 |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

32ビットのシアン、マゼンタ、イエロー、ブラック値から CMYK を作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| シアン | int | シアン成分。 有効な値は 0 から 255 です。 |
| マゼンタ | int | マゼンタ成分。 有効な値は 0 から 255 です。 |
| 黄 | int | イエロー成分。 有効な値は 0 から 255 です。 |
| 黒 | int | ブラック成分。 有効な値は 0 から 255 です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット整数値として表現された CMYK カラー。 |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

シアン成分の値を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk | int | 32 ビット整数値として表現された CMYK カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | シアン成分の値。 |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

ブラック成分の値を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk | int | 32 ビット整数値として表現された CMYK カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 黒コンポーネントの値です。 |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

マゼンタ成分の値を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk | int | 32 ビット整数値として表現された CMYK カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | マゼンタコンポーネントの値です。 |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

イエロー成分の値を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk | int | 32 ビット整数値として表現された CMYK カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 黄コンポーネントの値です。 |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

CMYK カラーから ARGB カラーへの変換。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB カラー。 |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

CMYK カラーから ARGB カラーへの変換。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixels | int | 32 ビット整数値として表現された CMYK カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB カラー。 |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

CMYK カラーから ARGB カラーへの変換。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixels | int | 32 ビット整数値として表現された CMYK カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット整数値として表現された ARGB カラー。 |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

デフォルトプロファイルを使用した ICC 変換により、CMYK カラーから ARGB カラーへの変換。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB カラー。 |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

CMYK カラーから ARGB カラーへの変換（カスタムプロファイルを使用した Icc 変換）。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc プロファイルを含むストリーム。 |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc プロファイルを含むストリーム。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB カラー。 |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

デフォルトプロファイルを使用した ICC 変換により、CMYK カラーから ARGB カラーへの変換。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixels | int | 32 ビット整数値として表現された CMYK ピクセル。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB カラー。 |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

CMYK カラーから ARGB カラーへの変換（カスタムプロファイルを使用した Icc 変換）。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixels | int | 32 ビット整数値として表現された CMYK カラー。 |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc プロファイルを含むストリーム。 |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc プロファイルを含むストリーム。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB カラー。 |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

ARGB カラーから CMYK カラーへの変換。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット整数値として表現された CMYK カラー。 |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

ARGB カラーから CMYK カラーへの変換。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| argb_pixels | int | 32 ビット整数値として表現された ARGB カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット整数値として表現された CMYK カラー。 |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

ARGB カラーから CMYK カラーへの変換。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット整数値として表現された CMYK カラー。 |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

ARGB カラーから CMYK カラーへの変換。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット整数値として表現された CMYK カラー。 |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

RGB を CMYK に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| argb_pixels | int | RGB カラーは 32 ビット整数値として表されます。 |
| start_index | int | RGB カラーの開始インデックスです。 |
| 長さを取得または設定します。 | int | 変換する RGB ピクセルの数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| byte | CMYK カラーはバイト配列として表されます。 |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

ARGB カラーから CMYK カラーへの変換（デフォルトプロファイルを使用した Icc 変換）。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット整数値として表現された CMYK カラー。 |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

ARGB カラーから CMYK カラーへの変換（カスタムプロファイルを使用した Icc 変換）。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc プロファイルを含むストリーム。 |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc プロファイルを含むストリーム。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット整数値として表現された CMYK カラー。 |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

ARGB カラーから CMYK カラーへの変換（デフォルトプロファイルを使用した Icc 変換）。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット整数値として表現された CMYK カラー。 |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

ARGB カラーから CMYK カラーへの変換（カスタムプロファイルを使用した Icc 変換）。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB カラー。 |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc プロファイルを含むストリーム。 |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc プロファイルを含むストリーム。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット整数値として表現された CMYK カラー。 |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

カスタム ICC プロファイルを使用して RGB を CMYK に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pixels | int | RGB カラーは 32 ビット整数値として表されます。 |
| start_index | int | RGB カラーの開始インデックスです。 |
| 長さを取得または設定します。 | int | 変換する RGB ピクセルの数です。 |
| rgb_icc_stream | _io.BufferedRandom | RGB プロファイル ストリームです。 |
| cmyk_icc_stream | _io.BufferedRandom | CMYK プロファイル ストリームです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| byte | CMYK カラーはバイト配列として表されます。 |


