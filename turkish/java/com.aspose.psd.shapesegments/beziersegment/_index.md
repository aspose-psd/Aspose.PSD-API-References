---
title: "BezierSegment"
second_title: "Java için Aspose.PSD API Referansı"
description: "İki kontrol noktası kullanarak bir noktadan bir sonraki noktaya giden bezier segmenti."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.shapesegments/beziersegment/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ShapeSegment](../../com.aspose.psd/shapesegment), [com.aspose.psd.shapesegments.LineSegment](../../com.aspose.psd.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

İki kontrol noktası kullanarak bir noktadan bir sonraki noktaya giden bezier segmenti.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | BezierSegment sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Bitiş noktasını alır. |
| [getFirstControlPoint()](#getFirstControlPoint--) | Bezier eğrisinin ilk kontrol noktasını alır. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Bezier eğrisinin ikinci kontrol noktasını alır. |
| [getStartPoint()](#getStartPoint--) | Başlangıç noktasını alır. |
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


BezierSegment sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.psd/pointf) | Başlangıç noktası. |
| firstControlPoint | [PointF](../../com.aspose.psd/pointf) | İlk kontrol noktası. |
| secondControlPoint | [PointF](../../com.aspose.psd/pointf) | İkinci kontrol noktası. |
| endPoint | [PointF](../../com.aspose.psd/pointf) | Bitiş noktası. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Bitiş noktasını alır.

Değer: Bitiş noktası.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Bezier eğrisinin ilk kontrol noktasını alır.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Bezier eğrisinin ikinci kontrol noktasını alır.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The second control point.
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Başlangıç noktasını alır.

Değer: Başlangıç noktası.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

