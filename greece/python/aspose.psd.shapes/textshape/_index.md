---
title: "Κλάση TextShape"
type: docs
weight: 90
url: /el/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [TextShape()](#TextShape__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Λαμβάνει τα όρια του αντικειμένου. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το κέντρο του σχήματος. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | Λαμβάνει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται για τη σχεδίαση του κειμένου. |
| has_segments | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν το σχήμα έχει τμήματα. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το αριστερό κάτω σημείο του ορθογωνίου. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το αριστερό άνω σημείο του ορθογωνίου. |
| rectangle_height | double | r | Λαμβάνει το ύψος του ορθογωνίου. |
| rectangle_width | double | r | Λαμβάνει το πλάτος του ορθογωνίου. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το δεξί κάτω σημείο του ορθογωνίου. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το δεξί άνω σημείο του ορθογωνίου. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Λαμβάνει τα τμήματα του σχήματος. |
| text | string | r/w | Λαμβάνει ή ορίζει το σχεδιασμένο κείμενο. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | Λαμβάνει ή ορίζει τη μορφή του κειμένου. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Λαμβάνει τα όρια του αντικειμένου. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Λαμβάνει τα όρια του αντικειμένου. |
| [transform(transform)](#transform_transform_3) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | string | Το κείμενο για σχεδίαση. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το ορθογώνιο του κειμένου. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Η γραμματοσειρά προς χρήση. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Η μορφή συμβολοσειράς. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Λαμβάνει τα όρια του αντικειμένου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο πίνακας που θα εφαρμοστεί πριν από τα όρια θα υπολογιστεί. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Τα εκτιμώμενα όρια του αντικειμένου. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Λαμβάνει τα όρια του αντικειμένου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο πίνακας που θα εφαρμοστεί πριν από τα όρια θα υπολογιστεί. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το στυλό που θα χρησιμοποιηθεί για το αντικείμενο. Αυτό μπορεί να επηρεάσει το μέγεθος των ορίων του αντικειμένου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Τα εκτιμώμενα όρια του αντικειμένου. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο μετασχηματισμός που θα εφαρμοστεί. |

