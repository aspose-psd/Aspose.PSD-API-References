---
title: TextShape Class
type: docs
weight: 90
url: /python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.6.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextShape()](#TextShape__1) | Initializes a new instance of the [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) class. |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Initializes a new instance of the [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Gets the object's bounds. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the shape's center. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | Gets or sets the font used to draw the text. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the left bottom rectangle point. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the left top rectangle point. |
| rectangle_height | double | r | Gets the rectangle height. |
| rectangle_width | double | r | Gets the rectangle width. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the right bottom rectangle point. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets the right top rectangle point. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Gets the shape segments. |
| text | string | r/w | Gets or sets the drawn text. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | Gets or sets the text format. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Gets the object's bounds. |
| [transform(transform)](#transform_transform_3) | Applies the specified transformation to the shape. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Initializes a new instance of the [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) class.

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Initializes a new instance of the [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| text | string | The text to draw. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The text rectangle. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | The font to use. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | The string format. |

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

