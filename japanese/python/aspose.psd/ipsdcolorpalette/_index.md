---
title: "IPsdColorPalette クラス"
type: docs
weight: 1990
url: /ja/python-net/aspose.psd/ipsdcolorpalette/
---

**Summary:** The pasd color palette

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPsdColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32ビットARGB構造体の配列を取得します。 |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | [Color](/psd/python-net/aspose.psd/color/) 構造体の配列を取得します。 |
| entries_count | int | r | エントリ数を取得します。 |
| has_transparent_color | bool | r | 透過色が存在するかどうかを示す値を取得します。 |
| is_compact_palette | bool | r | コンパクトパレットが使用されているかどうかを示す値を取得します。 |
| raw_entries | byte | r | 生のカラーパレットエントリデータを取得します。 |
| raw_entries_count | int | r | 生のカラーパレットエントリ数を取得します。 |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | 透過色を取得します。 |
| transparent_index | short | r | 透過色のインデックスを取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | インデックスで指定された32ビットARGBパレットカラーを取得します。 |
| [get_color(index)](#get_color_index_2) | インデックスで指定されたパレットカラーを取得します。 |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | 最も近い32ビットARGBカラーのインデックスを取得します。 |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | 最も近い32ビットARGBカラーのインデックスを取得します。 |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

最も近い32ビットARGBカラーのインデックスを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| argb_32_color | int | 32ビットARGBカラーです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 最も近いカラーのインデックスです。 |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

最も近い32ビットARGBカラーのインデックスを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 最も近いカラーのインデックスです。 |


