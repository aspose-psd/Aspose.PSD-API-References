---
title: Pen Class
type: docs
weight: 3290
url: /python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Initializes a new instance of the [Pen](/psd/python-net/aspose.psd/pen/) class with the specified [Pen.brush](/psd/python-net/aspose.psd/pen/). |
| [Pen(brush, width)](#Pen_brush_width_2) | Initializes a new instance of the [Pen](/psd/python-net/aspose.psd/pen/) class with the specified [Pen.brush](/psd/python-net/aspose.psd/pen/) and [Pen.width](/psd/python-net/aspose.psd/pen/). |
| [Pen(color)](#Pen_color_3) | Initializes a new instance of the [Pen](/psd/python-net/aspose.psd/pen/) class with the specified color. |
| [Pen(color, width)](#Pen_color_width_4) | Initializes a new instance of the [Pen](/psd/python-net/aspose.psd/pen/) class with the specified [Pen.color](/psd/python-net/aspose.psd/pen/) and [Pen.width](/psd/python-net/aspose.psd/pen/) properties. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | Gets or sets the alignment for this [Pen](/psd/python-net/aspose.psd/pen/). |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | Gets or sets the [Pen.brush](/psd/python-net/aspose.psd/pen/) that determines attributes of this [Pen](/psd/python-net/aspose.psd/pen/). |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Gets or sets the color of this [Pen](/psd/python-net/aspose.psd/pen/). |
| compound_array | float | r/w | Gets or sets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Gets or sets a custom cap to use at the end of lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Gets or sets a custom cap to use at the beginning of lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | Gets or sets the cap style used at the end of the dashes that make up dashed lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_offset | float | r/w | Gets or sets the distance from the start of a line to the beginning of a dash pattern. |
| dash_pattern | float | r/w | Gets or sets an array of custom dashes and spaces. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | Gets or sets the style used for dashed lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Gets or sets the cap style used at the end of lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Gets or sets the join style for the ends of two consecutive lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |
| miter_limit | float | r/w | Gets or sets the limit of the thickness of the join on a mitered corner. |
| opacity | float | r/w | Gets or sets the object's opacity. The value should be between 0 and 1. Value of 0 means that object is fully visible, value of 1 means the object is fully opaque. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | Gets the style of lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Gets or sets the cap style used at the beginning of lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Gets or sets a copy of the geometric transformation for this [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | r/w | Gets or sets the width of this [Pen](/psd/python-net/aspose.psd/pen/), in units of the Graphics object used for drawing. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | Multiplies the transformation matrix for this [Pen](/psd/python-net/aspose.psd/pen/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | Multiplies the transformation matrix for this [Pen](/psd/python-net/aspose.psd/pen/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) in the specified order. |
| reset_transform() | Resets the geometric transformation matrix for this [Pen](/psd/python-net/aspose.psd/pen/) to identity. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | Rotates the local geometric transformation by the specified angle. This method prepends the rotation to the transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | Rotates the local geometric transformation by the specified angle in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | Scales the local geometric transformation by the specified factors. This method prepends the scaling matrix to the transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | Scales the local geometric transformation by the specified factors in the specified order. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | Sets the values that determine the style of cap used to end lines drawn by this [Pen](/psd/python-net/aspose.psd/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Translates the local geometric transformation by the specified dimensions. This method prepends the translation to the transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Translates the local geometric transformation by the specified dimensions in the specified order. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Initializes a new instance of the [Pen](/psd/python-net/aspose.psd/pen/) class with the specified [Pen.brush](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | A [Pen.brush](/psd/python-net/aspose.psd/pen/) that determines the fill properties of this [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Initializes a new instance of the [Pen](/psd/python-net/aspose.psd/pen/) class with the specified [Pen.brush](/psd/python-net/aspose.psd/pen/) and [Pen.width](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | A [Pen.brush](/psd/python-net/aspose.psd/pen/) that determines the characteristics of this [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | The width of the new [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Initializes a new instance of the [Pen](/psd/python-net/aspose.psd/pen/) class with the specified color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | A [Pen.color](/psd/python-net/aspose.psd/pen/) structure that indicates the color of this [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Initializes a new instance of the [Pen](/psd/python-net/aspose.psd/pen/) class with the specified [Pen.color](/psd/python-net/aspose.psd/pen/) and [Pen.width](/psd/python-net/aspose.psd/pen/) properties.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | A [Pen.color](/psd/python-net/aspose.psd/pen/) structure that indicates the color of this [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | A value indicating the width of this [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

Multiplies the transformation matrix for this [Pen](/psd/python-net/aspose.psd/pen/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The [Matrix](/psd/python-net/aspose.psd/matrix/) object by which to multiply the transformation matrix. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

Multiplies the transformation matrix for this [Pen](/psd/python-net/aspose.psd/pen/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The [Matrix](/psd/python-net/aspose.psd/matrix/) by which to multiply the transformation matrix. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | The order in which to perform the multiplication operation. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

Rotates the local geometric transformation by the specified angle. This method prepends the rotation to the transformation.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transformation by the specified angle in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transformation by the specified factors. This method prepends the scaling matrix to the transformation.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The factor by which to scale the transformation in the x-axis direction. |
| sy | float | The factor by which to scale the transformation in the y-axis direction. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

Scales the local geometric transformation by the specified factors in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The factor by which to scale the transformation in the x-axis direction. |
| sy | float | The factor by which to scale the transformation in the y-axis direction. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies whether to append or prepend the scaling matrix. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Sets the values that determine the style of cap used to end lines drawn by this [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | A [LineCap](/psd/python-net/aspose.psd/linecap/) that represents the cap style to use at the beginning of lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | A [LineCap](/psd/python-net/aspose.psd/linecap/) that represents the cap style to use at the end of lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | A [LineCap](/psd/python-net/aspose.psd/linecap/) that represents the cap style to use at the beginning or end of dashed lines drawn with this [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transformation by the specified dimensions. This method prepends the translation to the transformation.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Translates the local geometric transformation by the specified dimensions in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | The order (prepend or append) in which to apply the translation. |

