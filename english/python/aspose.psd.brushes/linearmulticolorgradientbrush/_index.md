---
title: LinearMulticolorGradientBrush Class
type: docs
weight: 40
url: /python-net/aspose.psd.brushes/linearmulticolorgradientbrush/
---

**Summary:** Represents a [Brush](/psd/python-net/aspose.psd/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__1) | Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class with default parameters.<br/>            The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1). |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class with the specified points. |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_3) | Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class with the specified points. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_5) | Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7) | Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angle | float | r/w | Gets or sets the gradient angle. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| gamma_correction | bool | r/w | Gets or sets a value indicating whether gamma correction is enabled for this [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Gets or sets a [ColorBlend](/psd/python-net/aspose.psd/colorblend/) that defines a multicolor linear gradient. |
| is_angle_scalable | bool | r/w | Gets or sets a value indicating whether [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) is changed during trasnformations with this [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or<br/>            calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| opacity | float | r/w | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Gets or sets a rectangular region that defines the starting and ending points of the gradient. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Gets or sets a copy [Matrix](/psd/python-net/aspose.psd/matrix/) that defines a local geometric transform for this [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Gets or sets a [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enumeration that indicates the wrap mode for this [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Creates a new deep clone of the current [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) by prepending the specified [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) in the specified order. |
| reset_transform() | Resets the [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) property to identity. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Rotates the local geometric transform by the specified amount in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Scales the local geometric transform by the specified amounts in the specified order. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Translates the local geometric transform by the specified dimensions in the specified order. |


### Constructor: LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__1}


```
 LinearMulticolorGradientBrush() 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class with default parameters.<br/>            The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1).

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | A [Point](/psd/python-net/aspose.psd/point/) structure that represents the starting point of the linear gradient. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | A [Point](/psd/python-net/aspose.psd/point/) structure that represents the endpoint of the linear gradient. |

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_3}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | A [Point](/psd/python-net/aspose.psd/point/) structure that represents the starting point of the linear gradient. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | A [Point](/psd/python-net/aspose.psd/point/) structure that represents the endpoint of the linear gradient. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that specifies the bounds of the linear gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_5}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that specifies the bounds of the linear gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that specifies the bounds of the linear gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |
| is_angle_scalable | bool | if set to <c>true</c> the angle is changed during transformations with this [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/). |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that specifies the bounds of the linear gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |
| is_angle_scalable | bool | if set to <c>true</c> the angle is changed during transformations with this [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Creates a new deep clone of the current [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | A new [Brush](/psd/python-net/aspose.psd/brush/) which is the deep clone of this [Brush](/psd/python-net/aspose.psd/brush/) instance. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) by prepending the specified [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The [Matrix](/psd/python-net/aspose.psd/matrix/) by which to multiply the geometric transform. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The [Matrix](/psd/python-net/aspose.psd/matrix/) by which to multiply the geometric transform. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies in which order to multiply the two matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies whether to append or prepend the scaling matrix. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Translates the local geometric transform by the specified dimensions in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | The order (prepend or append) in which to apply the translation. |

