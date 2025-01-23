---
title: CurveShape Class
type: docs
weight: 30
url: /python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Initializes a new instance of the [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) class. |
| [CurveShape(points)](#CurveShape_points_2) | Initializes a new instance of the [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) class. The default tension of 0.5 is used. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Initializes a new instance of the [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) class. The default tension of 0.5 is used. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Initializes a new instance of the [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) class. |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Initializes a new instance of the [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Gets the object's bounds. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the shape's center. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the ending shape point. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| is_closed | bool | r/w | Gets or sets a value indicating whether shape is closed. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Gets or sets the curve points. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Gets the shape segments. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the starting shape point. |
| tension | float | r/w | Gets or sets the curve tension. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Gets the object's bounds. |
| reverse() | Reverses the order of points for this shape. |
| [transform(transform)](#transform_transform_3) | Applies the specified transformation to the shape. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Initializes a new instance of the [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) class.

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Initializes a new instance of the [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) class. The default tension of 0.5 is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | The points array. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Initializes a new instance of the [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) class. The default tension of 0.5 is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | The points array. |
| is_closed | bool | if set to <c>true</c> the curve is closed. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Initializes a new instance of the [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | The points array. |
| tension | float | The curve tension. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Initializes a new instance of the [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | The points array. |
| tension | float | The curve tension. |
| is_closed | bool | if set to <c>true</c> the curve is closed. |

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

