---
title: "BezierSegment"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Segmen bezier yang bergerak dari satu titik ke titik berikutnya dan menggunakan dua titik kontrol."
type: docs
weight: 10
url: /id/java/com.aspose.psd.shapesegments/beziersegment/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ShapeSegment](../../com.aspose.psd/shapesegment), [com.aspose.psd.shapesegments.LineSegment](../../com.aspose.psd.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

Segmen bezier yang bergerak dari satu titik ke titik berikutnya dan menggunakan dua titik kontrol.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Menginisialisasi sebuah instance baru dari kelas  BezierSegment . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Mendapatkan titik akhir. |
| [getFirstControlPoint()](#getFirstControlPoint--) | Mendapatkan titik kontrol pertama dari spline bezier. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Mendapatkan titik kontrol kedua dari spline bezier. |
| [getStartPoint()](#getStartPoint--) | Mendapatkan titik awal. |
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


Menginisialisasi sebuah instance baru dari kelas  BezierSegment .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.psd/pointf) | Titik awal. |
| firstControlPoint | [PointF](../../com.aspose.psd/pointf) | Titik kontrol pertama. |
| secondControlPoint | [PointF](../../com.aspose.psd/pointf) | Titik kontrol kedua. |
| endPoint | [PointF](../../com.aspose.psd/pointf) | Titik akhir. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mendapatkan titik akhir.

Nilai: Titik akhir.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Mendapatkan titik kontrol pertama dari spline bezier.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Mendapatkan titik kontrol kedua dari spline bezier.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The second control point.
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Mendapatkan titik awal.

Nilai: Titik awal.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

