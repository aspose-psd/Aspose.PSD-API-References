---
title: "PsdColorPalette クラス"
type: docs
weight: 1750
url: /ja/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | 新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32ビット ARGB カラーの配列を取得します。 |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | [Color](/psd/python-net/aspose.psd/color/) 構造体の配列を取得します。 |
| entries_count | int | r | エントリ数を取得します。 |
| has_transparent_color | bool | r | 透過色が存在するかどうかを示す値を取得します。 |
| is_compact_palette | bool | r | パレットがコンパクトかどうかを示す値を取得します。 |
| raw_entries | byte | r | 生のカラーパレットエントリデータを取得します。 |
| raw_entries_count | int | r | 生のカラーパレットエントリ数を取得します。 |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | 透過色を取得します。 |
| transparent_index | short | r | 透過色のインデックスを取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | パレットをコピーします。 |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | パレットをコピーします。 |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | インデックスで指定された32ビットARGBパレットカラーを取得します。 |
| [get_color(index)](#get_color_index_4) | インデックスで指定されたパレットカラーを取得します。 |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | 最も近い色のインデックスを取得します。 |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | 最も近い色のインデックスを取得します。 |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | カラーパレット。 |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | カラーパレット。 |
| transparent_index | short | 透過カラーインデックスです。 |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_palette_argb_32_entries | int | カラー パレットの 32 ビット ARGB エントリです。 |
| is_compact_palette | bool | コンパクト パレットかどうかを示します。 |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | カラー パレットのエントリです。 |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | カラー パレットのエントリです。 |
| is_compact_palette | bool | コンパクト パレットかどうかを示します。 |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | カラー パレットのエントリです。 |
| transparent_index | short | 透過カラーインデックスです。 |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | カラー パレットのエントリです。 |
| transparent_index | short | 透過カラーインデックスです。 |
| use_compact_palette | bool | コンパクト パレットかどうかを示します。 |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| raw_entries_data | byte | 生エントリ データです。 |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| raw_entries_data | byte | 生エントリ データです。 |
| is_compact_palette | bool | コンパクト パレットかどうかを示します。 |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| raw_entries_data | byte | 生エントリ データです。 |
| transparent_index | short | 透過カラーインデックスです。注：このインデックスは生エントリのインデックスではなく、変換されたカラー配列用のインデックスです。 |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

新しい [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| raw_entries_data | byte | 生エントリ データです。 |
| transparent_index | short | 透過カラーインデックスです。注：このインデックスは生エントリのインデックスではなく、変換されたカラー配列用のインデックスです。 |
| use_compact_palette | bool | コンパクト パレットかどうかを示します。 |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | 新しく作成されコピーされたパレット、または null パレットが渡された場合は null です。 |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | 新しく作成されコピーされたパレット、または null パレットが渡された場合は null です。 |


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


