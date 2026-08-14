---
title: "Κλάση Figure"
type: docs
weight: 1220
url: /el/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Figure()](#Figure__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης Figure |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Λαμβάνει ή ορίζει τα όρια του αντικειμένου. |
| is_closed | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το σχήμα είναι κλειστό. Ένα κλειστό σχήμα θα κάνει διαφορά μόνο στην περίπτωση όπου<br/>            τα σχήματα του πρώτου και του τελευταίου σχήματος είναι συνεχόμενα σχήματα. Σε αυτήν την περίπτωση το πρώτο σημείο του πρώτου σχήματος θα είναι<br/>            συνδεδεμένο με μια ευθεία γραμμή από το τελευταίο σημείο του τελευταίου σχήματος. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Λαμβάνει τα ολόκληρα τμήματα του σχήματος. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Λαμβάνει τα σχήματα του σχήματος. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Προσθέτει ένα σχήμα στο σχήμα. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Προσθέτει μια σειρά σχημάτων στο σχήμα. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Λαμβάνει τα όρια του αντικειμένου. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Λαμβάνει τα όρια του αντικειμένου. |
| [remove_shape(shape)](#remove_shape_shape_5) | Αφαιρεί ένα σχήμα από το σχήμα. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Αφαιρεί μια σειρά σχημάτων από το σχήμα. |
| reverse() | Αντιστρέφει τη σειρά των σχημάτων αυτού του σχήματος και τη σειρά των σημείων των σχημάτων. |
| [transform(transform)](#transform_transform_7) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης Figure

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Προσθέτει ένα σχήμα στο σχήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Το σχήμα προς προσθήκη. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Προσθέτει μια σειρά σχημάτων στο σχήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Τα σχήματα προς προσθήκη. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Αφαιρεί ένα σχήμα από το σχήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Το σχήμα προς αφαίρεση. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Αφαιρεί μια σειρά σχημάτων από το σχήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Η σειρά των σχημάτων προς αφαίρεση. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο μετασχηματισμός που θα εφαρμοστεί. |

