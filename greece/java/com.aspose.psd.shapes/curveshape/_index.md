---
title: "CurveShape"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά ένα σχήμα καμπυλωτής spline."
type: docs
weight: 12
url: /el/java/com.aspose.psd.shapes/curveshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Αναπαριστά ένα σχήμα καμπυλωτής spline.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CurveShape()](#CurveShape--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CurveShape . |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.psd.PointF---) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CurveShape . |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CurveShape . |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.psd.PointF---float-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CurveShape . |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---float-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CurveShape . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Λαμβάνει τα όρια του αντικειμένου. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Λαμβάνει τα όρια του αντικειμένου. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Λαμβάνει τα όρια του αντικειμένου. |
| [getCenter()](#getCenter--) | Αποκτά το κέντρο του σχήματος. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Λαμβάνει το σημείο λήξης του σχήματος. |
| [getPoints()](#getPoints--) | Λαμβάνει ή ορίζει τα σημεία της καμπύλης. |
| [getSegments()](#getSegments--) | Αποκτά τα τμήματα του σχήματος. |
| [getStartPoint()](#getStartPoint--) | Λαμβάνει το σημείο έναρξης του σχήματος. |
| [getTension()](#getTension--) | Λαμβάνει ή ορίζει την τάση της καμπύλης. |
| [hasSegments()](#hasSegments--) | Αποκτά μια τιμή που υποδεικνύει αν το σχήμα έχει τμήματα. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το σχήμα είναι κλειστό. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Αντιστρέφει τη σειρά των σημείων για αυτό το σχήμα. |
| [setClosed(boolean value)](#setClosed-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το σχήμα είναι κλειστό. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Λαμβάνει ή ορίζει τα σημεία της καμπύλης. |
| [setTension(float value)](#setTension-float-) | Λαμβάνει ή ορίζει την τάση της καμπύλης. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CurveShape .

### CurveShape(PointF[] points) {#CurveShape-com.aspose.psd.PointF---}
```
public CurveShape(PointF[] points)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CurveShape . Η προεπιλεγμένη τάση των 0.5 χρησιμοποιείται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Ο πίνακας σημείων. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CurveShape . Η προεπιλεγμένη τάση των 0.5 χρησιμοποιείται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Ο πίνακας σημείων. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.psd.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CurveShape .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Ο πίνακας σημείων. |
| τάση | float | Η τάση της καμπύλης. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CurveShape .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Ο πίνακας σημείων. |
| τάση | float | Η τάση της καμπύλης. |
| isClosed | boolean | εάν οριστεί σε  true  η καμπύλη είναι κλειστή. |

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
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Λαμβάνει το σημείο λήξης του σχήματος.

Τιμή: Το τελικό σημείο του σχήματος.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Λαμβάνει ή ορίζει τα σημεία της καμπύλης.

Τιμή: Τα σημεία της καμπύλης.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Αποκτά τα τμήματα του σχήματος.

Τιμή: Τα τμήματα του σχήματος.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Λαμβάνει το σημείο έναρξης του σχήματος.

Τιμή: Το αρχικό σημείο του σχήματος.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getTension() {#getTension--}
```
public float getTension()
```


Λαμβάνει ή ορίζει την τάση της καμπύλης.

Τιμή: Η τάση της καμπύλης.

**Returns:**
float
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
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το σχήμα είναι κλειστό.

Τιμή:  true  εάν το σχήμα είναι κλειστό· διαφορετικά,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reverse() {#reverse--}
```
public void reverse()
```


Αντιστρέφει τη σειρά των σημείων για αυτό το σχήμα.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το σχήμα είναι κλειστό.

Τιμή:  true  εάν το σχήμα είναι κλειστό· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


Λαμβάνει ή ορίζει τα σημεία της καμπύλης.

Τιμή: Τα σημεία της καμπύλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Λαμβάνει ή ορίζει την τάση της καμπύλης.

Τιμή: Η τάση της καμπύλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

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

