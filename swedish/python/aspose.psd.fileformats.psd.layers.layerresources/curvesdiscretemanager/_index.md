---
title: "CurvesDiscreteManager-klass"
type: docs
weight: 210
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Hämtar det maximala kanalantalet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | Hämtar värdet på positionen. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | Sätter till standardvärdet på positionen. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | Sätter värdet på positionen. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | Sätter värdet för hela kanalen. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

Hämtar värdet på positionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |
| position | byte | Positionen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Värde på kurvan efter dess position |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

Sätter till standardvärdet på positionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |
| position | byte | Positionen. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

Sätter värdet på positionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |
| position | byte | Positionen. |
| värde | byte | Värdet. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

Sätter värdet för hela kanalen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |
| channel_value | byte | Kanalvärdet. |

