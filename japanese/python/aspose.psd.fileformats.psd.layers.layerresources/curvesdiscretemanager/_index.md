---
title: "CurvesDiscreteManager クラス"
type: docs
weight: 210
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| max_channel_count | int | r | 最大チャネル数を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | 位置の値を取得します。 |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | 位置の値をデフォルトに設定します。 |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | 位置の値を設定します。 |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | チャネル全体の値を設定します。 |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

位置の値を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |
| position | byte | 位置。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| byte | 位置による曲線の値 |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

位置の値をデフォルトに設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |
| position | byte | 位置。 |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

位置の値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |
| position | byte | 位置。 |
| 値 | byte | 値です。 |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

チャネル全体の値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |
| channel_value | byte | チャネルの値。 |

