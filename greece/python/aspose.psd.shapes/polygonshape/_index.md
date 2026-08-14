---
title: "PolygonShape Κλάση"
type: docs
weight: 60
url: /el/python-net/aspose.psd.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
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


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ο πίνακας σημείων. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ο πίνακας σημείων. |
| is_closed | bool | Εάν οριστεί σε <c>true</c> το πολύγωνο είναι κλειστό. |

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

