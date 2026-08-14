---
title: "ColorRangeHsl クラス"
type: docs
weight: 180
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | 新しい [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) クラスのインスタンスを初期化します。 |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | 新しい [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| hue | short | r/w | 色相を取得または設定します。 |
| left_border | short | r/w | 左境界を取得または設定します。 |
| lightness | short | r/w | 明度を取得または設定します。 |
| most_left_border | short | r/w | 最左境界を取得または設定します。 |
| most_right_border | short | r/w | 最右境界を取得または設定します。 |
| right_border | short | r/w | 右境界を取得または設定します。 |
| saturation | short | r/w | saturation を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | 範囲係数を取得します。 |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | 色相が大きい範囲にあるかどうかを判定します。 |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | 色相が小さい範囲にあるかどうかを判定します。 |
| [save(stream_container)](#save_stream_container_4) | データを指定されたストリーム コンテナに保存します。 |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

新しい [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) クラスのインスタンスを初期化します。

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

新しい [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | カラー範囲データです。 |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

範囲係数を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| hue | double | 色相値です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| double | 彩度範囲係数です。 |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

色相が大きい範囲にあるかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| hue | double | 色相値です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <c>true</c> は色相が大きい範囲にある場合; それ以外の場合は <c>false</c>。 |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

色相が小さい範囲にあるかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| hue | double | 色相値です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 色相が小さい範囲にある場合は<c>true</c>、それ以外の場合は<c>false</c>です。 |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

データを指定されたストリーム コンテナに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |

