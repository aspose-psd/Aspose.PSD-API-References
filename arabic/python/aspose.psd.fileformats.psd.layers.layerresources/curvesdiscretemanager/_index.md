---
title: "فئة CurvesDiscreteManager"
type: docs
weight: 210
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| max_channel_count | int | r | يحصل على الحد الأقصى لعدد القنوات. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | يحصل على القيمة في الموضع. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | يضبط إلى القيمة الافتراضية في الموضع. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | يضبط القيمة في الموضع. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | يضبط قيمة القناة بالكامل. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

يحصل على القيمة في الموضع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |
| position | byte | الموضع. |

**Returns**

| النوع | الوصف |
| :- | :- |
| byte | قيمة المنحنى حسب موضعه |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

يضبط إلى القيمة الافتراضية في الموضع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |
| position | byte | الموضع. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

يضبط القيمة في الموضع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |
| position | byte | الموضع. |
| قيمة | byte | القيمة. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

يضبط قيمة القناة بالكامل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |
| channel_value | byte | قيمة القناة. |

