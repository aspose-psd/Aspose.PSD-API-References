---
title: "CurvesDiscreteManager Classe"
type: docs
weight: 210
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Obtient le nombre maximal de canaux. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | Obtient la valeur à la position. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | Définit la valeur par défaut à la position. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | Définit la valeur à la position. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | Définit la valeur de l'ensemble du canal. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

Obtient la valeur à la position.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |
| position | byte | La position. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Valeur de la courbe par sa position |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

Définit la valeur par défaut à la position.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |
| position | byte | La position. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

Définit la valeur à la position.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |
| position | byte | La position. |
| valeur | byte | La valeur. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

Définit la valeur de l'ensemble du canal.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |
| channel_value | byte | La valeur du canal. |

