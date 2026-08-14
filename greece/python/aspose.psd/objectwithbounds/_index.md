---
title: "ObjectWithBounds Κλάση"
type: docs
weight: 3170
url: /el/python-net/aspose.psd/objectwithbounds/
---

**Summary:** The object having bounds.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Λαμβάνει τα όρια του αντικειμένου. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Λαμβάνει τα όρια του αντικειμένου. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Λαμβάνει τα όρια του αντικειμένου. |
| [transform(transform)](#transform_transform_3) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |


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

