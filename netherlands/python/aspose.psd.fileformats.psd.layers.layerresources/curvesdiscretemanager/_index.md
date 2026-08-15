---
title: "CurvesDiscreteManager Klasse"
type: docs
weight: 210
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Haalt het maximale kanaalaantal op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | Haalt de waarde op op positie. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | Stelt in op de standaardwaarde op positie. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | Stelt de waarde in op positie. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | Stelt de waarde van het volledige kanaal in. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

Haalt de waarde op op positie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |
| position | byte | De positie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | Waarde van curve op basis van zijn positie |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

Stelt in op de standaardwaarde op positie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |
| position | byte | De positie. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

Stelt de waarde in op positie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |
| position | byte | De positie. |
| value | byte | De value. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

Stelt de waarde van het volledige kanaal in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |
| channel_value | byte | De kanaalwaarde. |

