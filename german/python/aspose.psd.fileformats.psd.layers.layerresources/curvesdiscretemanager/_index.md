---
title: "CurvesDiscreteManager Klasse"
type: docs
weight: 210
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Liefert die maximale Kanalanzahl. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | Liest den Wert an der Position. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | Setzt den Standardwert an der Position. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | Setzt den Wert an der Position. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | Setzt den Wert des gesamten Kanals. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

Liest den Wert an der Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |
| Position | byte | Die Position. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Wert der Kurve an ihrer Position |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

Setzt den Standardwert an der Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |
| Position | byte | Die Position. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

Setzt den Wert an der Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |
| Position | byte | Die Position. |
| Wert | byte | Der Wert. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

Setzt den Wert des gesamten Kanals.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |
| channel_value | byte | Der Kanalwert. |

