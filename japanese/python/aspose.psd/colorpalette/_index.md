---
title: "ColorPalette クラス"
type: docs
weight: 800
url: /ja/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。 |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) クラスの新しいインスタンスを初期化します。 |
| [ColorPalette(entries)](#ColorPalette_entries_3) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。 |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32ビットARGB構造体の配列を取得します。 |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | [Color](/psd/python-net/aspose.psd/color/) 構造体の配列を取得します。 |
| entries_count | int | r | エントリ数を取得します。 |
| is_compact_palette | bool | r | コンパクトパレットが使用されているかどうかを示す値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | パレットをコピーします。 |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | パレットをコピーします。 |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | インデックスで指定された32ビットARGBパレットカラーを取得します。 |
| [get_color(index)](#get_color_index_4) | インデックスで指定されたパレットカラーを取得します。 |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | 最も近い色のインデックスを取得します。 |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | 最も近い色のインデックスを取得します。 |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| argb_32_entries | int | 32ビット ARGB カラーパレット エントリ。 |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| argb_32_entries | int | 32ビット ARGB カラーパレット エントリ。 |
| is_compact_palette | bool | コンパクト パレットかどうかを示します。 |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) クラスの新しいインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | コンパクト パレットかどうかを示します。 |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

パレットをコピーします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | カラーパレット。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | 新しく作成されコピーされたパレット、または null パレットが渡された場合は null です。 |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

パレットをコピーします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | カラーパレット。 |
| use_compact_palette | bool | コンパクト パレットかどうかを示します。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | 新しく作成されコピーされたパレット、または null パレットが渡された場合は null です。 |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


```
 get_argb_32_color(index) 
```

インデックスで指定された32ビットARGBパレットカラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| index | int | 32ビットARGBパレットカラーのインデックスです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | <paramref name=\"index\" /> で指定されたカラーパレットエントリです。 |


### Method: get_color(index) {#get_color_index_4}


```
 get_color(index) 
```

インデックスで指定されたパレットカラーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| index | int | パレットカラーのインデックスです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | <paramref name=\"index\" /> で指定されたカラーパレットエントリです。 |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

最も近い色のインデックスを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| argb_32_color | int | 32ビットARGBカラーです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 最も近いカラーのインデックスです。 |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

最も近い色のインデックスを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 最も近いカラーのインデックスです。 |


