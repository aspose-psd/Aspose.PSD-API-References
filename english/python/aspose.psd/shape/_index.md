---
title: Shape Class
type: docs
weight: 3950
url: /python-net/aspose.psd/shape/
---

**Summary:** The shape. A continuous set of points connected using a specific rule.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Shape

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.1.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Gets the object's bounds. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the shape's center. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Gets the shape segments. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Gets the object's bounds. |
| [transform(transform)](#transform_transform_3) | Applies the specified transformation to the shape. |


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

