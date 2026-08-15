---
title: "TextShape Klasse"
type: docs
weight: 90
url: /nl/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [TextShape()](#TextShape__1) | Initialiseert een nieuw exemplaar van de [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) klasse. |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Initialiseert een nieuw exemplaar van de [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Haalt de grenzen van het object op. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het midden van de vorm op. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | Haalt het lettertype op dat wordt gebruikt om de tekst te tekenen of stelt dit in. |
| has_segments | bool | r | Haalt een waarde op die aangeeft of de vorm segmenten heeft. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het linksonderhoekpunt van de rechthoek op. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het linkerbovenhoekpunt van de rechthoek op. |
| rectangle_height | double | r | Haalt de hoogte van de rechthoek op. |
| rectangle_width | double | r | Haalt de breedte van de rechthoek op. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het rechtsonderhoekpunt van de rechthoek op. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het rechterbovenhoekpunt van de rechthoek op. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Haalt de segmenten van de vorm op. |
| text | string | r/w | Haalt de getekende tekst op of stelt deze in. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | Haalt het tekstformaat op of stelt dit in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Haalt de grenzen van het object op. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Haalt de grenzen van het object op. |
| [transform(transform)](#transform_transform_3) | Past de opgegeven transformatie toe op de vorm. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Initialiseert een nieuw exemplaar van de [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) klasse.

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Initialiseert een nieuw exemplaar van de [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | string | De te tekenen tekst. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De tekstrechthoek. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Het te gebruiken lettertype. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Het tekenreeksformaat. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Haalt de grenzen van het object op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De geschatte grenzen van het object. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Haalt de grenzen van het object op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De pen die voor het object wordt gebruikt. Dit kan de grootte van de objectgrenzen beïnvloeden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De geschatte grenzen van het object. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Past de opgegeven transformatie toe op de vorm.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | De toe te passen transformatie. |

