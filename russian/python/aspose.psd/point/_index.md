---
title: "Класс Point"
type: docs
weight: 3530
url: /ru/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Point()](#Point__1) | Инициализирует новый экземпляр класса Point |
| [Point(dw)](#Point_dw_2) | Инициализирует новый экземпляр структуры [Point](/psd/python-net/aspose.psd/point/) с использованием координат, указанных целочисленным значением. |
| [Point(size)](#Point_size_3) | Инициализирует новый экземпляр структуры [Point](/psd/python-net/aspose.psd/point/) из структуры [Size](/psd/python-net/aspose.psd/size/). |
| [Point(x, y)](#Point_x_y_4) | Инициализирует новый экземпляр структуры [Point](/psd/python-net/aspose.psd/point/) с указанными координатами. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | Получает новый экземпляр структуры [Point](/psd/python-net/aspose.psd/point/), у которого значения [Point.x](/psd/python-net/aspose.psd/point/) и [Point.y](/psd/python-net/aspose.psd/point/) установлены в ноль. |
| is_empty | bool | r | Получает значение, указывающее, пустой ли этот [Point](/psd/python-net/aspose.psd/point/). |
| x | int | r/w | Получает или задает координату x этого [Point](/psd/python-net/aspose.psd/point/). |
| y | int | r/w | Получает или задает координату y этого [Point](/psd/python-net/aspose.psd/point/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Добавляет указанный [Size](/psd/python-net/aspose.psd/size/) к указанному [Point](/psd/python-net/aspose.psd/point/). |
| [ceiling(point)](#ceiling_point_2) | Преобразует указанный [PointF](/psd/python-net/aspose.psd/pointf/) в [Point](/psd/python-net/aspose.psd/point/) путем округления значений [PointF](/psd/python-net/aspose.psd/pointf/) до следующего большего целого значения. |
| [offset(dx, dy)](#offset_dx_dy_3) | Перемещает этот [Point](/psd/python-net/aspose.psd/point/) на указанную величину. |
| [offset(point)](#offset_point_4) | Перемещает этот [Point](/psd/python-net/aspose.psd/point/) на указанный [Point](/psd/python-net/aspose.psd/point/). |
| [round(point)](#round_point_5) | Преобразует указанный [PointF](/psd/python-net/aspose.psd/pointf/) в объект [Point](/psd/python-net/aspose.psd/point/) путем округления значений [Point](/psd/python-net/aspose.psd/point/) до ближайшего целого. |
| [subtract(point, size)](#subtract_point_size_6) | Возвращает результат вычитания указанного [Size](/psd/python-net/aspose.psd/size/) из указанного [Point](/psd/python-net/aspose.psd/point/). |
| [truncate(point)](#truncate_point_7) | Преобразует указанный [PointF](/psd/python-net/aspose.psd/pointf/) в [Point](/psd/python-net/aspose.psd/point/) путем усечения значений [Point](/psd/python-net/aspose.psd/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Инициализирует новый экземпляр класса Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Инициализирует новый экземпляр структуры [Point](/psd/python-net/aspose.psd/point/) с использованием координат, указанных целочисленным значением.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dw | int | 32-битное целое число, задающее координаты новой точки. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Инициализирует новый экземпляр структуры [Point](/psd/python-net/aspose.psd/point/) из структуры [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Содержит координаты новой точки. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Инициализирует новый экземпляр структуры [Point](/psd/python-net/aspose.psd/point/) с указанными координатами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Горизонтальная позиция точки. |
| y | int | Вертикальная позиция точки. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Добавляет указанный [Size](/psd/python-net/aspose.psd/size/) к указанному [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Точка [Point](/psd/python-net/aspose.psd/point/) для добавления. |
| size | [Size](/psd/python-net/aspose.psd/size) | Размер [Size](/psd/python-net/aspose.psd/size/) для добавления к <paramref name=\"point\" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Точка [Point](/psd/python-net/aspose.psd/point/) — результат операции сложения. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Преобразует указанный [PointF](/psd/python-net/aspose.psd/pointf/) в [Point](/psd/python-net/aspose.psd/point/) путем округления значений [PointF](/psd/python-net/aspose.psd/pointf/) до следующего большего целого значения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Точка [Point](/psd/python-net/aspose.psd/point/), в которую преобразует этот метод. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

Перемещает этот [Point](/psd/python-net/aspose.psd/point/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | int | Величина смещения координаты x. |
| dy | int | Величина смещения координаты y. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

Перемещает этот [Point](/psd/python-net/aspose.psd/point/) на указанный [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Точка [Point](/psd/python-net/aspose.psd/point/) используется для смещения этой [Point](/psd/python-net/aspose.psd/point/). |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

Преобразует указанный [PointF](/psd/python-net/aspose.psd/pointf/) в объект [Point](/psd/python-net/aspose.psd/point/) путем округления значений [Point](/psd/python-net/aspose.psd/point/) до ближайшего целого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Точка [Point](/psd/python-net/aspose.psd/point/), в которую преобразует этот метод. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Возвращает результат вычитания указанного [Size](/psd/python-net/aspose.psd/size/) из указанного [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Точка [Point](/psd/python-net/aspose.psd/point/) из которой будет вычитаться. |
| size | [Size](/psd/python-net/aspose.psd/size) | Размер [Size](/psd/python-net/aspose.psd/size/) для вычитания из <paramref name=\"point\" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Точка [Point](/psd/python-net/aspose.psd/point/) — результат операции вычитания. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

Преобразует указанный [PointF](/psd/python-net/aspose.psd/pointf/) в [Point](/psd/python-net/aspose.psd/point/) путем усечения значений [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Точка [Point](/psd/python-net/aspose.psd/point/), в которую преобразует этот метод. |


