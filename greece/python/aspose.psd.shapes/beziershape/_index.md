---
title: "Κλάση BezierShape"
type: docs
weight: 20
url: /el/python-net/aspose.psd.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/). |
| [BezierShape(points)](#BezierShape_points_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/). |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Λαμβάνει τα όρια του αντικειμένου. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το κέντρο του σχήματος. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το τελικό σημείο του σχήματος. |
| has_segments | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν το σχήμα έχει τμήματα. |
| is_closed | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το σχήμα είναι κλειστό. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Λαμβάνει ή ορίζει τα σημεία της καμπύλης. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Λαμβάνει τα τμήματα του σχήματος. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει το αρχικό σημείο του σχήματος. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Λαμβάνει τα όρια του αντικειμένου. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Λαμβάνει τα όρια του αντικειμένου. |
| reverse() | Αντιστρέφει τη σειρά των σημείων για αυτό το σχήμα. |
| [transform(transform)](#transform_transform_3) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/).

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ο πίνακας σημείων. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ο πίνακας σημείων. |
| is_closed | bool | Εάν οριστεί σε <c>true</c> η καμπύλη Bezier είναι κλειστή. |

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

