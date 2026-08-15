---
title: "Clase TextShape"
type: docs
weight: 90
url: /es/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TextShape()](#TextShape__1) | Inicializa una nueva instancia de la clase [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Inicializa una nueva instancia de la clase [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtiene los límites del objeto. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el centro de la forma. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | Obtiene o establece la fuente utilizada para dibujar el texto. |
| has_segments | bool | r | Obtiene un valor que indica si la forma tiene segmentos. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto inferior izquierdo del rectángulo. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto superior izquierdo del rectángulo. |
| rectangle_height | double | r | Obtiene la altura del rectángulo. |
| rectangle_width | double | r | Obtiene el ancho del rectángulo. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto inferior derecho del rectángulo. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto superior derecho del rectángulo. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtiene los segmentos de la forma. |
| text | string | r/w | Obtiene o establece el texto dibujado. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | Obtiene o establece el formato del texto. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Inicializa una nueva instancia de la clase [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Inicializa una nueva instancia de la clase [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | string | El texto a dibujar. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo de texto. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | La fuente a usar. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | El formato de cadena. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Obtiene los límites del objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matriz a aplicar antes de los límites será calculada. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Los límites estimados del objeto. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Obtiene los límites del objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matriz a aplicar antes de los límites será calculada. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | El lápiz a usar para el objeto. Esto puede influir en el tamaño de los límites del objeto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Los límites estimados del objeto. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Aplica la transformación especificada a la forma.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La transformación a aplicar. |

