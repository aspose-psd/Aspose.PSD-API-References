---
title: "Clase CurvesDiscreteManager"
type: docs
weight: 210
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Obtiene el número máximo de canales. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | Obtiene el valor en la posición. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | Establece el valor predeterminado en la posición. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | Establece el valor en la posición. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | Establece el valor de todo el canal. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

Obtiene el valor en la posición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |
| position | byte | La posición. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Valor de la curva por su posición |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

Establece el valor predeterminado en la posición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |
| position | byte | La posición. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

Establece el valor en la posición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |
| position | byte | La posición. |
| value | byte | El valor. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

Establece el valor de todo el canal.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |
| channel_value | byte | El valor del canal. |

