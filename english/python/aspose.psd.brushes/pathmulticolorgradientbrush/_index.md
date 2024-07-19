---
title: PathMulticolorGradientBrush Class
type: docs
weight: 70
url: /python-net/aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified path. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_2) | Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_3) | Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_4) | Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_5) | Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Gets or sets the center point of the path gradient. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Gets or sets the focus point for the gradient falloff. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Gets the graphics path this brush was build upon. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Gets or sets a [ColorBlend](/psd/python-net/aspose.psd/colorblend/) that defines a multicolor linear gradient. |
| is_transform_changed | bool | r | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or<br/>            calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| opacity | float | r/w | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Gets the path points this brush was build upon. |
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


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | The [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) that defines the area filled by this [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/). |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_2}


```
 PathMulticolorGradientBrush(points) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_3}


```
 PathMulticolorGradientBrush(points) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | A [WrapMode](/psd/python-net/aspose.psd/wrapmode/) that specifies how fills drawn with this [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) are tiled. |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | A [WrapMode](/psd/python-net/aspose.psd/wrapmode/) that specifies how fills drawn with this [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) are tiled. |

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

