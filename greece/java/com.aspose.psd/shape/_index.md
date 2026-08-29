---
title: "Σχήμα"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το σχήμα."
type: docs
weight: 96
url: /el/java/com.aspose.psd/shape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

Το σχήμα. Ένα συνεχές σύνολο σημείων συνδεδεμένων με συγκεκριμένο κανόνα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Shape()](#Shape--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Λαμβάνει τα όρια του αντικειμένου. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Λαμβάνει τα όρια του αντικειμένου. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Λαμβάνει τα όρια του αντικειμένου. |
| [getCenter()](#getCenter--) | Αποκτά το κέντρο του σχήματος. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Αποκτά τα τμήματα του σχήματος. |
| [hasSegments()](#hasSegments--) | Αποκτά μια τιμή που υποδεικνύει αν το σχήμα έχει τμήματα. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


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
public abstract RectangleF getBounds()
```


Λαμβάνει τα όρια του αντικειμένου.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public abstract RectangleF getBounds(Matrix matrix)
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
public abstract RectangleF getBounds(Matrix matrix, Pen pen)
```


Λαμβάνει τα όρια του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η μήτρα που θα εφαρμοστεί πριν υπολογιστούν τα όρια. |
| pen | [Pen](../../com.aspose.psd/pen) | Το στυλό που θα χρησιμοποιηθεί για το αντικείμενο. Αυτό μπορεί να επηρεάσει το μέγεθος των ορίων του αντικειμένου. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Αποκτά το κέντρο του σχήματος.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The shape's center.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Αποκτά τα τμήματα του σχήματος.

**Returns:**
com.aspose.psd.ShapeSegment[] - Τα τμήματα του σχήματος.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Αποκτά μια τιμή που υποδεικνύει αν το σχήμα έχει τμήματα.

**Returns:**
boolean -  True εάν το σχήμα έχει τμήματα· διαφορετικά, false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public abstract void transform(Matrix transform)
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

