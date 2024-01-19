---
title: RectangleShape Class
type: docs
weight: 80
url: /python-net/aspose.psd.shapes/rectangleshape/
---

**Summary:** Represents a rectangular shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.RectangleShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleShape()](#RectangleShape__1) | Initializes a new instance of the [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/) class. |
| [RectangleShape(rectangle)](#RectangleShape_rectangle_2) | Initializes a new instance of the [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Gets the object's bounds. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the shape's center. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the left bottom rectangle point. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the left top rectangle point. |
| rectangle_height | double | r | Gets the rectangle height. |
| rectangle_width | double | r | Gets the rectangle width. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the right bottom rectangle point. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the right top rectangle point. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Gets the shape segments. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Gets the object's bounds. |
| [transform(transform)](#transform_transform_3) | Applies the specified transformation to the shape. |


### Constructor: RectangleShape() {#RectangleShape__1}


```
 RectangleShape() 
```

Initializes a new instance of the [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/) class.

### Constructor: RectangleShape(rectangle) {#RectangleShape_rectangle_2}


```
 RectangleShape(rectangle) 
```

Initializes a new instance of the [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The rectangle. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The matrix to apply before bounds will be calculated. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The estimated object's bounds. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | The pen to use for object. This can influence the object's bounds size. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The estimated object's bounds. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | The transformation to apply. |

