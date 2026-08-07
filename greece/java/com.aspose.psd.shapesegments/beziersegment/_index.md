---
title: "BezierSegment"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το τμήμα Bézier που πηγαίνει από ένα σημείο στο επόμενο σημείο και χρησιμοποιεί δύο σημεία ελέγχου."
type: docs
weight: 10
url: /el/java/com.aspose.psd.shapesegments/beziersegment/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ShapeSegment](../../com.aspose.psd/shapesegment), [com.aspose.psd.shapesegments.LineSegment](../../com.aspose.psd.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

Το τμήμα Bézier που πηγαίνει από ένα σημείο στο επόμενο σημείο και χρησιμοποιεί δύο σημεία ελέγχου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Αρχικοποιεί μια νέα παρουσία της  BezierSegment  κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Λαμβάνει το τελικό σημείο. |
| [getFirstControlPoint()](#getFirstControlPoint--) | Λαμβάνει το πρώτο σημείο ελέγχου μιας καμπύλης bezier. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Λαμβάνει το δεύτερο σημείο ελέγχου μιας καμπύλης bezier. |
| [getStartPoint()](#getStartPoint--) | Λαμβάνει το αρχικό σημείο. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


Αρχικοποιεί μια νέα παρουσία της  BezierSegment  κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.psd/pointf) | Το σημείο εκκίνησης. |
| firstControlPoint | [PointF](../../com.aspose.psd/pointf) | Το πρώτο σημείο ελέγχου. |
| secondControlPoint | [PointF](../../com.aspose.psd/pointf) | Το δεύτερο σημείο ελέγχου. |
| endPoint | [PointF](../../com.aspose.psd/pointf) | Το σημείο λήξης. |

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


Λαμβάνει το τελικό σημείο.

Τιμή: Το σημείο λήξης.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Λαμβάνει το πρώτο σημείο ελέγχου μιας καμπύλης bezier.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Λαμβάνει το δεύτερο σημείο ελέγχου μιας καμπύλης bezier.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The second control point.
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Λαμβάνει το αρχικό σημείο.

Τιμή: Το σημείο εκκίνησης.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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

