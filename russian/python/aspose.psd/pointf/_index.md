---
title: "Класс PointF"
type: docs
weight: 3550
url: /ru/python-net/aspose.psd/pointf/
---

**Summary:** Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PointF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PointF()](#PointF__1) | Инициализирует новый экземпляр класса PointF |
| [PointF(x, y)](#PointF_x_y_2) | Инициализирует новый экземпляр структуры [PointF](/psd/python-net/aspose.psd/pointf/) с указанными координатами. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| empty [static] | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает новый экземпляр структуры [PointF](/psd/python-net/aspose.psd/pointf/), у которой значения [PointF.x](/psd/python-net/aspose.psd/pointf/) и [PointF.y](/psd/python-net/aspose.psd/pointf/) установлены в ноль. |
| is_empty | bool | r | Получает значение, указывающее, пустой ли этот [PointF](/psd/python-net/aspose.psd/pointf/). |
| x | float | r/w | Получает или задает координату x этого [PointF](/psd/python-net/aspose.psd/pointf/). |
| y | float | r/w | Получает или задает координату y этого [PointF](/psd/python-net/aspose.psd/pointf/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Перемещает заданный [PointF](/psd/python-net/aspose.psd/pointf/) на указанную [Size](/psd/python-net/aspose.psd/size/). |
| [add(point, size)](#add_point_size_2) | Перемещает заданный [PointF](/psd/python-net/aspose.psd/pointf/) на указанную [Size](/psd/python-net/aspose.psd/size/). |
| [subtract(point, size)](#subtract_point_size_3) | Перемещает [PointF](/psd/python-net/aspose.psd/pointf/) на отрицательное значение указанного размера. |
| [subtract(point, size)](#subtract_point_size_4) | Перемещает [PointF](/psd/python-net/aspose.psd/pointf/) на отрицательное значение указанного размера. |


### Constructor: PointF() {#PointF__1}


```
 PointF() 
```

Инициализирует новый экземпляр класса PointF

### Constructor: PointF(x, y) {#PointF_x_y_2}


```
 PointF(x, y) 
```

Инициализирует новый экземпляр структуры [PointF](/psd/python-net/aspose.psd/pointf/) с указанными координатами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Горизонтальная позиция точки. |
| y | float | Вертикальная позиция точки. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Перемещает заданный [PointF](/psd/python-net/aspose.psd/pointf/) на указанную [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Элемент [PointF](/psd/python-net/aspose.psd/pointf/) для перевода. |
| size | [Size](/psd/python-net/aspose.psd/size) | Элемент [Size](/psd/python-net/aspose.psd/size/), который указывает числа для добавления к координатам <paramref name="point" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Переведённый [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: add(point, size)  [static] {#add_point_size_2}


```
 add(point, size) 
```

Перемещает заданный [PointF](/psd/python-net/aspose.psd/pointf/) на указанную [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Элемент [PointF](/psd/python-net/aspose.psd/pointf/) для перевода. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Элемент [Size](/psd/python-net/aspose.psd/size/), который указывает числа для добавления к координатам <paramref name="point" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Переведённый [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_3}


```
 subtract(point, size) 
```

Перемещает [PointF](/psd/python-net/aspose.psd/pointf/) на отрицательное значение указанного размера.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Элемент [PointF](/psd/python-net/aspose.psd/pointf/) для перевода. |
| size | [Size](/psd/python-net/aspose.psd/size) | Элемент [Size](/psd/python-net/aspose.psd/size/), который указывает числа для вычитания из координат <paramref name="point" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Переведённый [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_4}


```
 subtract(point, size) 
```

Перемещает [PointF](/psd/python-net/aspose.psd/pointf/) на отрицательное значение указанного размера.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Элемент [PointF](/psd/python-net/aspose.psd/pointf/) для перевода. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Элемент [Size](/psd/python-net/aspose.psd/size/), который указывает числа для вычитания из координат <paramref name="point" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Переведённый [PointF](/psd/python-net/aspose.psd/pointf/). |


