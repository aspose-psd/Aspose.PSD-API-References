---
title: "Κλάση ArcShape"
type: docs
weight: 10
url: /el/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Λαμβάνει τα όρια του αντικειμένου. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το κέντρο του σχήματος. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το τελικό σημείο του σχήματος. |
| has_segments | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν το σχήμα έχει τμήματα. |
| is_closed | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το διατεταγμένο σχήμα είναι κλειστό. Κατά την επεξεργασία κλειστού διατεταγμένου σχήματος τα αρχικά και τελικά σημεία δεν έχουν νόημα. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το αριστερό κάτω σημείο του ορθογωνίου. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το αριστερό άνω σημείο του ορθογωνίου. |
| rectangle_height | double | r | Λαμβάνει το ύψος του ορθογωνίου. |
| rectangle_width | double | r | Λαμβάνει το πλάτος του ορθογωνίου. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το δεξί κάτω σημείο του ορθογωνίου. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το δεξί άνω σημείο του ορθογωνίου. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Λαμβάνει τα τμήματα του σχήματος. |
| start_angle | float | r/w | Λαμβάνει ή ορίζει τη γωνία εκκίνησης. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το αρχικό σημείο του σχήματος. |
| sweep_angle | float | r/w | Λαμβάνει ή ορίζει τη γωνία σάρωσης. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Λαμβάνει τα όρια του αντικειμένου. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Λαμβάνει τα όρια του αντικειμένου. |
| reverse() | Αντιστρέφει τη σειρά των σημείων για αυτό το σχήμα. |
| [transform(transform)](#transform_transform_3) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το ορθογώνιο. |
| start_angle | float | Η γωνία εκκίνησης. |
| sweep_angle | float | Η γωνία σάρωσης. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το ορθογώνιο. |
| start_angle | float | Η γωνία εκκίνησης. |
| sweep_angle | float | Η γωνία σάρωσης. |
| is_closed | bool | Εάν οριστεί σε <c>true</c> το τόξο είναι κλειστό. Το κλειστό τόξο στην πραγματικότητα εκφυλίζεται σε έλλειψη. |

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

