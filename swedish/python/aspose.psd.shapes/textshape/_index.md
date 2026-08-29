---
title: "TextShape-klass"
type: docs
weight: 90
url: /sv/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [TextShape()](#TextShape__1) | Initierar en ny instans av klassen [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Initierar en ny instans av klassen [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Hämtar objektets gränser. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar formens centrum. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | Hämtar eller anger teckensnittet som används för att rita texten. |
| has_segments | bool | r | Hämtar ett värde som indikerar om formen har segment. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar rektangelns nedre vänstra punkt. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar rektangelns övre vänstra punkt. |
| rectangle_height | double | r | Hämtar rektangelns höjd. |
| rectangle_width | double | r | Hämtar rektangelns bredd. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar rektangelns nedre högra punkt. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar den högra övre rektangelpunkten. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Hämtar formens segment. |
| text | string | r/w | Hämtar eller anger den ritade texten. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | Hämtar eller anger textformatet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Hämtar objektets gränser. |
| [transform(transform)](#transform_transform_3) | Tillämpar den angivna transformationen på formen. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Initierar en ny instans av klassen [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Initierar en ny instans av klassen [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | string | Texten att rita. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Textrektangeln. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Teckensnittet att använda. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Strängformatet. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriserna som ska tillämpas innan gränser beräknas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Det uppskattade objektets gränser. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriserna som ska tillämpas innan gränser beräknas. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Pennan som ska användas för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Det uppskattade objektets gränser. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Tillämpar den angivna transformationen på formen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Transformationen att tillämpa. |

