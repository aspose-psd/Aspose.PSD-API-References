---
title: "Κλάση CurveShape"
type: docs
weight: 30
url: /el/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Η προεπιλεγμένη τάση 0.5 χρησιμοποιείται. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Η προεπιλεγμένη τάση 0.5 χρησιμοποιείται. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
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
| τάση | float | r/w | Λαμβάνει ή ορίζει την τάση της καμπύλης. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Λαμβάνει τα όρια του αντικειμένου. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Λαμβάνει τα όρια του αντικειμένου. |
| reverse() | Αντιστρέφει τη σειρά των σημείων για αυτό το σχήμα. |
| [transform(transform)](#transform_transform_3) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Η προεπιλεγμένη τάση 0.5 χρησιμοποιείται.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ο πίνακας σημείων. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Η προεπιλεγμένη τάση 0.5 χρησιμοποιείται.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ο πίνακας σημείων. |
| is_closed | bool | εάν οριστεί σε <c>true</c> η καμπύλη είναι κλειστή. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ο πίνακας σημείων. |
| τάση | float | Η τάση της καμπύλης. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ο πίνακας σημείων. |
| τάση | float | Η τάση της καμπύλης. |
| is_closed | bool | εάν οριστεί σε <c>true</c> η καμπύλη είναι κλειστή. |

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

