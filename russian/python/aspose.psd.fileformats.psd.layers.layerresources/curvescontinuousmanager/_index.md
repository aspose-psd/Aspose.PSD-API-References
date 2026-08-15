---
title: "Класс CurvesContinuousManager"
type: docs
weight: 200
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Инициализирует новый экземпляр класса [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Получает максимальное количество каналов. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Добавляет точку кривой. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Получает точку кривой по индексу. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Получает количество точек кривой. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Удаляет точку кривой. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Обновляет точку кривой. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Инициализирует новый экземпляр класса [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| max_channel_count | int | Максимальное количество каналов. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Добавляет точку кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |
| x | байт | Координата x. |
| y | байт | Координата y. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Получает точку кривой по индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |
| point_index | int | Индекс точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Точка кривой по индексу канала |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Получает количество точек кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Количество точек кривой в канале |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Удаляет точку кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |
| point_index | int | Индекс точки. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Обновляет точку кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |
| point_index | int | Индекс точки. |
| x | байт | Координата x. |
| y | байт | Координата y. |

