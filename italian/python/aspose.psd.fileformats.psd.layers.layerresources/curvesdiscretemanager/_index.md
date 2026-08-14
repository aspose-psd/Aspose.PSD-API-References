---
title: "CurvesDiscreteManager Classe"
type: docs
weight: 210
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Restituisce il conteggio massimo dei canali. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | Ottiene il valore in posizione. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | Imposta al valore predefinito in posizione. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | Imposta il valore in posizione. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | Imposta il valore dell'intero canale. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

Ottiene il valore in posizione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |
| position | byte | La posizione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | Valore della curva in base alla sua posizione |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

Imposta al valore predefinito in posizione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |
| position | byte | La posizione. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

Imposta il valore in posizione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |
| position | byte | La posizione. |
| value | byte | Il valore. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

Imposta il valore dell'intero canale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |
| channel_value | byte | Il valore del canale. |

