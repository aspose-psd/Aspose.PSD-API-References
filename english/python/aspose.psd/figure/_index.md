---
title: Figure Class
type: docs
weight: 1170
url: /python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Figure()](#Figure__1) | Initializes a new instance of the Figure class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Gets or sets the object's bounds. |
| is_closed | bool | r/w | Gets or sets a value indicating whether this figure is closed. A closed figure will make a difference only in case where<br/>            the first and the last figure's shapes are continuous shapes. In such case the first point of the first shape will be<br/>            connected by a straight line from the last point of the last shape. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Gets the whole figure segments. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Gets the figure shapes. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Adds a shape to the figure. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Adds a range of shapes to the figure. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Gets the object's bounds. |
| [remove_shape(shape)](#remove_shape_shape_5) | Removes a shape from the figure. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Removes a range of shapes from the figure. |
| reverse() | Reverses this figure shapes order and shapes point order. |
| [transform(transform)](#transform_transform_7) | Applies the specified transformation to the shape. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Initializes a new instance of the Figure class

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Adds a shape to the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | The shape to add. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Adds a range of shapes to the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | The shapes to add. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Removes a shape from the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | The shape to remove. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Removes a range of shapes from the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | The shapes range to remove. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | The transformation to apply. |

