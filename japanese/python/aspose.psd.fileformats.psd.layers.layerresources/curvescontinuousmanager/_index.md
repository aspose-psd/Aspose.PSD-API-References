---
title: "CurvesContinuousManager クラス"
type: docs
weight: 200
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | 新しい [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| max_channel_count | int | r | 最大チャネル数を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | 曲線のポイントを追加します。 |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | インデックスで曲線のポイントを取得します。 |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | 曲線のポイント数を取得します。 |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | 曲線のポイントを削除します。 |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | 曲線のポイントを更新します。 |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

新しい [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| max_channel_count | int | 最大チャネル数です。 |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

曲線のポイントを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |
| x | byte | x 座標です。 |
| y | byte | y 座標です。 |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

インデックスで曲線のポイントを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |
| point_index | int | ポイントのインデックスです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | チャネルのインデックスによる曲線ポイント |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

曲線のポイント数を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | チャネル内の曲線ポイント数 |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

曲線のポイントを削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |
| point_index | int | ポイントのインデックスです。 |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

曲線のポイントを更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |
| point_index | int | ポイントのインデックスです。 |
| x | byte | x 座標です。 |
| y | byte | y 座標です。 |

