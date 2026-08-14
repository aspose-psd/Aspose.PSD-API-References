---
title: "CmykColor クラス"
type: docs
weight: 630
url: /ja/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | CmykColor クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| c | byte | r | この [Color](/psd/python-net/aspose.psd/color/) 構造体のシアン成分の値を取得します。 |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | 空の値を取得します。 |
| is_empty | bool | r | この [Color](/psd/python-net/aspose.psd/color/) 構造体が初期化されていないかどうかを示す値を取得します。 |
| k | byte | r | この [Color](/psd/python-net/aspose.psd/color/) 構造体のブラック成分の値を取得します。 |
| m | byte | r | この [Color](/psd/python-net/aspose.psd/color/) 構造体のマゼンタ成分の値を取得します。 |
| y | byte | r | この [Color](/psd/python-net/aspose.psd/color/) 構造体のイエロー成分の値を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | 32ビットのシアン、マゼンタ、イエロー、ブラック値から [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) 構造体を作成します。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。 |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から 32 ビット ARGB Color への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。 |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | 32 ビット ARGB カラーから CMYKColor への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。 |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | 32 ビット ARGB カラーから CMYKColor への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。 |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。 |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。 |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。 |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) を使用してください。 |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。 |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) を使用してください。 |
| [to_value()](#to_value__11) | to の値です。 |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

CmykColor クラスの新しいインスタンスを初期化します

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

32ビットのシアン、マゼンタ、イエロー、ブラック値から [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) 構造体を作成します。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。

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
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | 次の [CmykColor](/psd/python-net/aspose.psd/cmykcolor/)。 |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

デフォルトプロファイルを使用した ICC 変換により、CMYKColor から 32 ビット ARGB Color への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 形式の CMYKColor タイプのピクセルです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 32 ビット ARGB カラーの配列です。 |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

32 ビット ARGB カラーから CMYKColor への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | 次の <see cref="T:Aspose:PSD:CmykColor[]" />。 |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

32 ビット ARGB カラーから CMYKColor への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| argb_pixels | int | 32 ビット ARGB 形式のピクセルです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | 次の <see cref="T:Aspose:PSD:CmykColor[]" />。 |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB カラーの配列です。 |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 形式の CMYKColor タイプのピクセルです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB カラーの配列です。 |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | この [Color[]](/psd/python-net/aspose.psd/color/)。 |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) を使用してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | icc cmyk プロファイルを含むストリームです。 |
| rgb_icc_stream | _io.BufferedRandom | icc rgb プロファイルを含むストリームです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | この [Color[]](/psd/python-net/aspose.psd/color/)。 |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) を使用してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 形式の CMYKColor タイプのピクセルです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | この [Color[]](/psd/python-net/aspose.psd/color/)。 |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

ICC 変換により、CMYKColor から Color への変換です。<br/>            このメソッドは非推奨です。より効果的な Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) を使用してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK 形式の CMYKColor タイプのピクセルです。 |
| cmyk_icc_stream | _io.BufferedRandom | icc cmyk プロファイルを含むストリームです。 |
| rgb_icc_stream | _io.BufferedRandom | icc rgb プロファイルを含むストリームです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | この [Color[]](/psd/python-net/aspose.psd/color/)。 |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

to の値です。

**Returns**

| タイプ | 説明 |
| :- | :- |
| long | int 型です。 |


