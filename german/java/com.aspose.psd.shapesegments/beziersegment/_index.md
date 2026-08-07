---
title: "BezierSegment"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Das Bézier-Segment, das von einem Punkt zum nächsten Punkt verläuft und zwei Kontrollpunkte verwendet."
type: docs
weight: 10
url: /de/java/com.aspose.psd.shapesegments/beziersegment/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ShapeSegment](../../com.aspose.psd/shapesegment), [com.aspose.psd.shapesegments.LineSegment](../../com.aspose.psd.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

Das Bézier-Segment, das von einem Punkt zum nächsten Punkt verläuft und zwei Kontrollpunkte verwendet.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Initialisiert eine neue Instanz der  BezierSegment  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Liefert den Endpunkt. |
| [getFirstControlPoint()](#getFirstControlPoint--) | Liefert den ersten Kontrollpunkt eines Bezier-Splines. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Liefert den zweiten Kontrollpunkt eines Bezier-Splines. |
| [getStartPoint()](#getStartPoint--) | Liefert den Startpunkt. |
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


Initialisiert eine neue Instanz der  BezierSegment  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.psd/pointf) | Der Startpunkt. |
| firstControlPoint | [PointF](../../com.aspose.psd/pointf) | Der erste Kontrollpunkt. |
| secondControlPoint | [PointF](../../com.aspose.psd/pointf) | Der zweite Kontrollpunkt. |
| endPoint | [PointF](../../com.aspose.psd/pointf) | Der Endpunkt. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Liefert den Endpunkt.

Wert: Der Endpunkt.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Liefert den ersten Kontrollpunkt eines Bezier-Splines.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Liefert den zweiten Kontrollpunkt eines Bezier-Splines.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The second control point.
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Liefert den Startpunkt.

Wert: Der Startpunkt.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

