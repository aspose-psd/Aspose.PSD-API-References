---
title: "Класс CurvesDiscreteManager"
type: docs
weight: 210
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Получает максимальное количество каналов. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | Получает значение в позиции. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | Устанавливает значение по умолчанию в позиции. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | Устанавливает значение в позиции. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | Устанавливает значение всего канала. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

Получает значение в позиции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |
| position | байт | Позиция. |

**Returns**

| Тип | Описание |
| :- | :- |
| байт | Значение кривой по её позиции |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

Устанавливает значение по умолчанию в позиции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |
| position | байт | Позиция. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

Устанавливает значение в позиции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |
| position | байт | Позиция. |
| значение | байт | Значение. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

Устанавливает значение всего канала.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |
| channel_value | байт | Значение канала. |

