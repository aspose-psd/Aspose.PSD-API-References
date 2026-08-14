---
title: "ColorPaletteHelper クラス"
type: docs
weight: 810
url: /ja/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | 4ビット カラーパレットを作成します。 |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | 4ビット グレースケール パレットを作成します。 |
| [create_8_bit()](#create_8_bit__3) | 8ビット カラーパレットを作成します。 |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | 8ビット グレースケール パレットを作成します。 |
| [create_monochrome()](#create_monochrome__5) | 2色だけを含むモノクロ カラーパレットを作成します。 |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | 画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。 |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | 画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。 |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | 画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。 |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | 初期画像のカラー値の上位ビットから構成された 256 色カラーパレットを取得します。 |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | 均一な 256 色カラーパレットを取得します。 |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | 指定されたパレットに透明色があるかどうかを判定します。 |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

4ビット カラーパレットを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4ビット カラーパレットです。 |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

4ビット グレースケール パレットを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| min_is_white | bool | <c>true</c> に設定された場合、パレットは白色から開始し、そうでない場合は黒色から開始します。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4 ビットのグレースケール パレットです。 |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

8ビット カラーパレットを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 8 ビットのカラーパレットです。 |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

8ビット グレースケール パレットを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| min_is_white | bool | <c>true</c> に設定された場合、パレットは白色から開始し、そうでない場合は黒色から開始します。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 8 ビットのグレースケール パレットです。 |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

2色だけを含むモノクロ カラーパレットを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | モノクロ画像用のカラーパレットです。 |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | AiFinalizeSection Class |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 対象画像の境界です。 |
| entries_count | int | 希望するエントリ数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 画像 (<paramref name="image" />) から最も頻出する色で始まり、<paramref name="entriesCount" /> エントリを含むカラーパレットです。 |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | AiFinalizeSection Class |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 対象画像の境界です。 |
| entries_count | int | 希望するエントリ数です。 |
| use_image_palette | bool | 設定された場合、利用可能であれば独自の画像パレットを使用します。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 画像 (<paramref name="image" />) から最も頻出する色で始まり、<paramref name="entriesCount" /> エントリを含むカラーパレットです。 |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | AiFinalizeSection Class |
| entries_count | int | 希望するエントリ数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 画像 (<paramref name="image" />) から最も頻出する色で始まり、<paramref name="entriesCount" /> エントリを含むカラーパレットです。 |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

初期画像のカラー値の上位ビットから構成された 256 色カラーパレットを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 画像。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | この [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)。 |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

均一な 256 色カラーパレットを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 画像。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | この [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)。 |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

指定されたパレットに透明色があるかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | このパレットです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定されたパレットに透明色が含まれる場合は <c>true</c>、それ以外の場合は <c>false</c>です。 |


