---
title: "Класс PieShape"
type: docs
weight: 50
url: /ru/python-net/aspose.psd.shapes/pieshape/
---

**Summary:** Represents a pie shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PieShape

**Inheritance:** EllipseShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PieShape()](#PieShape__1) | Инициализирует новый экземпляр класса [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/). |
| [PieShape(rectangle, start_angle, sweep_angle)](#PieShape_rectangle_start_angle_sweep_angle_2) | Инициализирует новый экземпляр класса [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Получает границы объекта. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает центр фигуры. |
| has_segments | bool | r | Получает значение, указывающее, имеет ли фигура сегменты. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает левую нижнюю точку прямоугольника. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает левую верхнюю точку прямоугольника. |
| rectangle_height | double | r | Получает высоту прямоугольника. |
| rectangle_width | double | r | Получает ширину прямоугольника. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает правую нижнюю точку прямоугольника. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает правую верхнюю точку прямоугольника. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Получает сегменты фигуры. |
| start_angle | float | r/w | Получает или задает начальный угол. |
| sweep_angle | float | r/w | Получает или задает угол разворота. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Получает границы объекта. |
| [transform(transform)](#transform_transform_3) | Применяет указанное преобразование к фигуре. |


### Constructor: PieShape() {#PieShape__1}


```
 PieShape() 
```

Инициализирует новый экземпляр класса [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/).

### Constructor: PieShape(rectangle, start_angle, sweep_angle) {#PieShape_rectangle_start_angle_sweep_angle_2}


```
 PieShape(rectangle, start_angle, sweep_angle) 
```

Инициализирует новый экземпляр класса [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник. |
| start_angle | float | Начальный угол. |
| sweep_angle | float | Угол разворота. |

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

