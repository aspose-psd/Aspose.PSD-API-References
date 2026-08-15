---
title: "Класс CurveShape"
type: docs
weight: 30
url: /ru/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Инициализирует новый экземпляр класса [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Инициализирует новый экземпляр класса [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Используется значение натяжения по умолчанию 0.5. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Инициализирует новый экземпляр класса [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Используется значение натяжения по умолчанию 0.5. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Инициализирует новый экземпляр класса [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Инициализирует новый экземпляр класса [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Получает границы объекта. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает центр фигуры. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает конечную точку фигуры. |
| has_segments | bool | r | Получает значение, указывающее, имеет ли фигура сегменты. |
| is_closed | bool | r/w | Получает или задает значение, указывающее, замкнута ли фигура. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Получает или задает точки кривой. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Получает сегменты фигуры. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает начальную точку фигуры. |
| натяжение | float | r/w | Получает или задает натяжение кривой. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Получает границы объекта. |
| reverse() | Изменяет порядок точек для этой формы. |
| [transform(transform)](#transform_transform_3) | Применяет указанное преобразование к фигуре. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Инициализирует новый экземпляр класса [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Инициализирует новый экземпляр класса [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Используется значение натяжения по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив точек. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Инициализирует новый экземпляр класса [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Используется значение натяжения по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив точек. |
| is_closed | bool | Если установлено значение <c>true</c>, кривая замкнута. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Инициализирует новый экземпляр класса [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив точек. |
| натяжение | float | Натяжение кривой. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Инициализирует новый экземпляр класса [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив точек. |
| натяжение | float | Натяжение кривой. |
| is_closed | bool | Если установлено значение <c>true</c>, кривая замкнута. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица, применяемая перед вычислением границ, будет рассчитана. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Оценочные границы объекта. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица, применяемая перед вычислением границ, будет рассчитана. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Перо, используемое для объекта. Это может влиять на размер границ объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Оценочные границы объекта. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Применяет указанное преобразование к фигуре.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Преобразование для применения. |

