---
title: "EllipseShape"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά ένα σχήμα έλλειψης."
type: docs
weight: 13
url: /el/java/com.aspose.psd.shapes/ellipseshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape)
```
public class EllipseShape extends RectangleShape
```

Αναπαριστά ένα σχήμα έλλειψης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [EllipseShape()](#EllipseShape--) | Αρχικοποιεί μια νέα παρουσία της κλάσης  EllipseShape  . |
| [EllipseShape(RectangleF rectangle)](#EllipseShape-com.aspose.psd.RectangleF-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  EllipseShape  . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Λαμβάνει τα όρια του αντικειμένου. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Λαμβάνει τα όρια του αντικειμένου. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Λαμβάνει τα όρια του αντικειμένου. |
| [getCenter()](#getCenter--) | Αποκτά το κέντρο του σχήματος. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Λαμβάνει το αριστερό κάτω σημείο του ορθογωνίου. |
| [getLeftTop()](#getLeftTop--) | Λαμβάνει το αριστερό άνω σημείο του ορθογωνίου. |
| [getRectangleHeight()](#getRectangleHeight--) | Λαμβάνει το ύψος του ορθογωνίου. |
| [getRectangleWidth()](#getRectangleWidth--) | Λαμβάνει το πλάτος του ορθογωνίου. |
| [getRightBottom()](#getRightBottom--) | Λαμβάνει το δεξί κάτω σημείο του ορθογωνίου. |
| [getRightTop()](#getRightTop--) | Λαμβάνει το δεξί άνω σημείο του ορθογωνίου. |
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
### EllipseShape() {#EllipseShape--}
```
public EllipseShape()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  EllipseShape  .

### EllipseShape(RectangleF rectangle) {#EllipseShape-com.aspose.psd.RectangleF-}
```
public EllipseShape(RectangleF rectangle)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  EllipseShape  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Το ορθογώνιο. |

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


Λαμβάνει τα όρια του αντικειμένου.

Τιμή: Τα όρια του αντικειμένου.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
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
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Αποκτά το κέντρο του σχήματος.

Τιμή: Το κέντρο του σχήματος.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Λαμβάνει το αριστερό κάτω σημείο του ορθογωνίου.

Τιμή: Το αριστερό κάτω σημείο του ορθογωνίου.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Λαμβάνει το αριστερό άνω σημείο του ορθογωνίου.

Τιμή: Το αριστερό άνω σημείο του ορθογωνίου.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Λαμβάνει το ύψος του ορθογωνίου.

Τιμή: Το ύψος του ορθογωνίου.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Λαμβάνει το πλάτος του ορθογωνίου.

Τιμή: Το πλάτος του ορθογωνίου.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Λαμβάνει το δεξί κάτω σημείο του ορθογωνίου.

Τιμή: Το δεξί κάτω σημείο του ορθογωνίου.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Λαμβάνει το δεξί άνω σημείο του ορθογωνίου.

Τιμή: Το δεξί άνω σημείο του ορθογωνίου.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Αποκτά τα τμήματα του σχήματος.

Τιμή: Τα τμήματα του σχήματος.

**Returns:**
com.aspose.psd.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Αποκτά μια τιμή που υποδεικνύει αν το σχήμα έχει τμήματα.

Τιμή:  True  εάν το σχήμα έχει τμήματα· διαφορετικά,  false .

**Returns:**
boolean
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

