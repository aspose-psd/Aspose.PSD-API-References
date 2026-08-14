---
title: "Classe TextShape"
type: docs
weight: 90
url: /it/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextShape()](#TextShape__1) | Inizializza una nuova istanza della classe [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Inizializza una nuova istanza della classe [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Ottiene i limiti dell'oggetto. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il centro della forma. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | Ottiene o imposta il carattere usato per disegnare il testo. |
| has_segments | bool | r | Ottiene un valore che indica se la forma ha segmenti. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in basso a sinistra del rettangolo. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in alto a sinistra del rettangolo. |
| rectangle_height | double | r | Ottiene l'altezza del rettangolo. |
| rectangle_width | double | r | Ottiene la larghezza del rettangolo. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in basso a destra del rettangolo. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in alto a destra del rettangolo. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Ottiene i segmenti della forma. |
| text | string | r/w | Ottiene o imposta il testo disegnato. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | Ottiene o imposta il formato del testo. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Ottiene i limiti dell'oggetto. |
| [transform(transform)](#transform_transform_3) | Applica la trasformazione specificata alla forma. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Inizializza una nuova istanza della classe [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Inizializza una nuova istanza della classe [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | string | Il testo da disegnare. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo del testo. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Il carattere da usare. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Il formato della stringa. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice da applicare prima dei limiti sarà calcolata. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | I limiti stimati dell'oggetto. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice da applicare prima dei limiti sarà calcolata. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La penna da usare per l'oggetto. Questo può influenzare la dimensione dei limiti dell'oggetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | I limiti stimati dell'oggetto. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applica la trasformazione specificata alla forma.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La trasformazione da applicare. |

