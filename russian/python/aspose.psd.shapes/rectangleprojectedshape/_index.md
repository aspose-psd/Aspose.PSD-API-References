---
title: "Класс RectangleProjectedShape"
type: docs
weight: 70
url: /ru/python-net/aspose.psd.shapes/rectangleprojectedshape/
---

**Summary:** Represents a shape which is projected over rectangle turned to a particular orientation.<br/>            Specified by four points which can be rotated in space maintaining the same edges length and 90 degrees between adjacent edges.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.RectangleProjectedShape

**Inheritance:** Shape

**Aspose.PSD Version:** 24.12.0

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
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Получает границы объекта. |
| [transform(transform)](#transform_transform_3) | Применяет указанное преобразование к фигуре. |


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

