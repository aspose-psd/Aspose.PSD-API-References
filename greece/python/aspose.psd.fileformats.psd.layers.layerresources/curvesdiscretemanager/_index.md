---
title: "CurvesDiscreteManager Class"
type: docs
weight: 210
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Λαμβάνει το μέγιστο πλήθος καναλιών. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | Λαμβάνει την τιμή στη θέση. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | Ορίζει στην προεπιλεγμένη τιμή στη θέση. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | Ορίζει την τιμή στη θέση. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | Ορίζει την τιμή ολόκληρου του καναλιού. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

Λαμβάνει την τιμή στη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |
| position | byte | Η θέση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Τιμή της καμπύλης με βάση τη θέση της. |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

Ορίζει στην προεπιλεγμένη τιμή στη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |
| position | byte | Η θέση. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

Ορίζει την τιμή στη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |
| position | byte | Η θέση. |
| value | byte | Η value. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

Ορίζει την τιμή ολόκληρου του καναλιού.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |
| channel_value | byte | Η τιμή του καναλιού. |

