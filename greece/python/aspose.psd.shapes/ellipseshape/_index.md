---
title: "Κλάση EllipseShape"
type: docs
weight: 40
url: /el/python-net/aspose.psd.shapes/ellipseshape/
---

**Summary:** Represents an ellipse shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.EllipseShape

**Inheritance:** RectangleShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [EllipseShape()](#EllipseShape__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [EllipseShape](/psd/python-net/aspose.psd.shapes/ellipseshape/). |
| [EllipseShape(rectangle)](#EllipseShape_rectangle_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [EllipseShape](/psd/python-net/aspose.psd.shapes/ellipseshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Λαμβάνει τα όρια του αντικειμένου. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το κέντρο του σχήματος. |
| has_segments | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν το σχήμα έχει τμήματα. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το αριστερό κάτω σημείο του ορθογωνίου. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το αριστερό άνω σημείο του ορθογωνίου. |
| rectangle_height | double | r | Λαμβάνει το ύψος του ορθογωνίου. |
| rectangle_width | double | r | Λαμβάνει το πλάτος του ορθογωνίου. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το δεξί κάτω σημείο του ορθογωνίου. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το δεξί άνω σημείο του ορθογωνίου. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Λαμβάνει τα τμήματα του σχήματος. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Λαμβάνει τα όρια του αντικειμένου. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Λαμβάνει τα όρια του αντικειμένου. |
| [transform(transform)](#transform_transform_3) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |


### Constructor: EllipseShape() {#EllipseShape__1}


```
 EllipseShape() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [EllipseShape](/psd/python-net/aspose.psd.shapes/ellipseshape/).

### Constructor: EllipseShape(rectangle) {#EllipseShape_rectangle_2}


```
 EllipseShape(rectangle) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [EllipseShape](/psd/python-net/aspose.psd.shapes/ellipseshape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το ορθογώνιο. |

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

