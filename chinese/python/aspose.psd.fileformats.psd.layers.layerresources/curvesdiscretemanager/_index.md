---
title: "CurvesDiscreteManager 类"
type: docs
weight: 210
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_channel_count | int | r | 获取最大通道数。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | 获取该位置的值。 |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | 将该位置设置为默认值。 |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | 设置该位置的值。 |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | 设置整个通道的值。 |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

获取该位置的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |
| position | byte | 位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 曲线在其位置的值 |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

将该位置设置为默认值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |
| position | byte | 位置。 |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

设置该位置的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |
| position | byte | 位置。 |
| value | byte | 值。 |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

设置整个通道的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |
| channel_value | byte | 通道值。 |

