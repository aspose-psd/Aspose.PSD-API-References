---
title: "Σχήμα"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το σχήμα"
type: docs
weight: 42
url: /el/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

Η μορφή. Ένα δοχείο για σχήματα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Figure()](#Figure--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Προσθέτει ένα σχήμα στη μορφή. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Προσθέτει μια σειρά σχήματων στη μορφή. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Λαμβάνει ή ορίζει τα όρια του αντικειμένου. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Λαμβάνει τα όρια του αντικειμένου. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Λαμβάνει τα όρια του αντικειμένου. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Λαμβάνει τα τμήματα ολόκληρης της μορφής. |
| [getShapes()](#getShapes--) | Λαμβάνει τα σχήματα της μορφής. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Λαμβάνει μια τιμή που υποδεικνύει αν αυτή η μορφή είναι κλειστή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Αφαιρεί ένα σχήμα από τη μορφή. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Αφαιρεί μια σειρά σχήματων από τη μορφή. |
| [reverse()](#reverse--) | Αντιστρέφει τη σειρά των σχημάτων αυτής της μορφής και τη σειρά των σημείων των σχημάτων. |
| [setClosed(boolean value)](#setClosed-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν αυτή η μορφή είναι κλειστή. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Figure() {#Figure--}
```
public Figure()
```


### addShape(Shape shape) {#addShape-com.aspose.psd.Shape-}
```
public void addShape(Shape shape)
```


Προσθέτει ένα σχήμα στη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Το σχήμα προς προσθήκη. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Προσθέτει μια σειρά σχήματων στη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Τα σχήματα προς προσθήκη. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Λαμβάνει ή ορίζει τα όρια του αντικειμένου.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Λαμβάνει τα όρια του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η μήτρα που θα εφαρμοστεί πριν υπολογιστούν τα όρια. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Λαμβάνει τα όρια του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η μήτρα που θα εφαρμοστεί πριν υπολογιστούν τα όρια. |
| pen | [Pen](../../com.aspose.psd/pen) | Το στυλό που θα χρησιμοποιηθεί για το αντικείμενο. Αυτό μπορεί να επηρεάσει το μέγεθος των ορίων του αντικειμένου. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Λαμβάνει τα τμήματα ολόκληρης της μορφής.

**Returns:**
com.aspose.psd.ShapeSegment[] - Τα τμήματα της μορφής.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Λαμβάνει τα σχήματα της μορφής.

**Returns:**
com.aspose.psd.Shape[] - Τα σχήματα της μορφής.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Λαμβάνει μια τιμή που υποδεικνύει αν αυτή η μορφή είναι κλειστή. Μια κλειστή μορφή θα κάνει διαφορά μόνο στην περίπτωση όπου τα πρώτα και τα τελευταία σχήματα της μορφής είναι συνεχόμενα σχήματα. Σε αυτήν την περίπτωση, το πρώτο σημείο του πρώτου σχήματος θα συνδεθεί με ευθεία γραμμή από το τελευταίο σημείο του τελευταίου σχήματος.

**Returns:**
boolean -  True  αν αυτή η μορφή είναι κλειστή· διαφορετικά,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeShape(Shape shape) {#removeShape-com.aspose.psd.Shape-}
```
public void removeShape(Shape shape)
```


Αφαιρεί ένα σχήμα από τη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Το σχήμα προς αφαίρεση. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Αφαιρεί μια σειρά σχήματων από τη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Η σειρά σχήματων προς αφαίρεση. |

### reverse() {#reverse--}
```
public void reverse()
```


Αντιστρέφει τη σειρά των σχημάτων αυτής της μορφής και τη σειρά των σημείων των σχημάτων.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει αν αυτή η μορφή είναι κλειστή. Μια κλειστή μορφή θα κάνει διαφορά μόνο στην περίπτωση όπου τα πρώτα και τα τελευταία σχήματα της μορφής είναι συνεχόμενα σχήματα. Σε αυτήν την περίπτωση, το πρώτο σημείο του πρώτου σχήματος θα συνδεθεί με ευθεία γραμμή από το τελευταίο σημείο του τελευταίου σχήματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Αληθές εάν αυτό το σχήμα είναι κλειστό· διαφορετικά, ψευδές. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Η μετατροπή που θα εφαρμοστεί. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

