---
title: "CurvesDiscreteManager 클래스"
type: docs
weight: 210
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| max_channel_count | int | r | 최대 채널 수를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | 해당 위치의 값을 가져옵니다. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | 해당 위치를 기본값으로 설정합니다. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | 해당 위치에 값을 설정합니다. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | 전체 채널의 값을 설정합니다. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

해당 위치의 값을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |
| position | byte | 위치. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| byte | 곡선의 위치에 따른 값 |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

해당 위치를 기본값으로 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |
| position | byte | 위치. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

해당 위치에 값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |
| position | byte | 위치. |
| 값 | byte | 값입니다. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

전체 채널의 값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |
| channel_value | byte | 채널 값. |

