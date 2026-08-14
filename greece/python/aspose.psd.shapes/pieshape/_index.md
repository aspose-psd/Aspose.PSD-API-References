---
title: "Κλάση PieShape"
type: docs
weight: 50
url: /el/python-net/aspose.psd.shapes/pieshape/
---

**Summary:** Represents a pie shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PieShape

**Inheritance:** EllipseShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PieShape()](#PieShape__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/). |
| [PieShape(rectangle, start_angle, sweep_angle)](#PieShape_rectangle_start_angle_sweep_angle_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/). |
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
| start_angle | float | r/w | Λαμβάνει ή ορίζει τη γωνία εκκίνησης. |
| sweep_angle | float | r/w | Λαμβάνει ή ορίζει τη γωνία σάρωσης. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Λαμβάνει τα όρια του αντικειμένου. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Λαμβάνει τα όρια του αντικειμένου. |
| [transform(transform)](#transform_transform_3) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |


### Constructor: PieShape() {#PieShape__1}


```
 PieShape() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/).

### Constructor: PieShape(rectangle, start_angle, sweep_angle) {#PieShape_rectangle_start_angle_sweep_angle_2}


```
 PieShape(rectangle, start_angle, sweep_angle) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το ορθογώνιο. |
| start_angle | float | Η γωνία εκκίνησης. |
| sweep_angle | float | Η γωνία σάρωσης. |

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

