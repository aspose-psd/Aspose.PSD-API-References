---
title: "BezierSegment"
second_title: "Aspose.PSD för Java API-referens"
description: "Bezier-segmentet som går från en punkt till nästa punkt och använder två kontrollpunkter."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.shapesegments/beziersegment/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ShapeSegment](../../com.aspose.psd/shapesegment), [com.aspose.psd.shapesegments.LineSegment](../../com.aspose.psd.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

Bezier-segmentet som går från en punkt till nästa punkt och använder två kontrollpunkter.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Initierar en ny instans av klassen BezierSegment. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Hämtar slutpunkten. |
| [getFirstControlPoint()](#getFirstControlPoint--) | Hämtar den första kontrollpunkten för en bezier-spline. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Hämtar den andra kontrollpunkten för en bezier-spline. |
| [getStartPoint()](#getStartPoint--) | Hämtar startpunkten. |
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


Initierar en ny instans av klassen BezierSegment.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.psd/pointf) | Startpunkten. |
| firstControlPoint | [PointF](../../com.aspose.psd/pointf) | Den första kontrollpunkten. |
| secondControlPoint | [PointF](../../com.aspose.psd/pointf) | Den andra kontrollpunkten. |
| endPoint | [PointF](../../com.aspose.psd/pointf) | Slutpunkten. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar slutpunkten.

Värde: Slutpunkten.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Hämtar den första kontrollpunkten för en bezier-spline.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Hämtar den andra kontrollpunkten för en bezier-spline.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The second control point.
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Hämtar startpunkten.

Värde: Startpunkten.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

