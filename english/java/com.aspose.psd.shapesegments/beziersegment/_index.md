---
title: BezierSegment
second_title: Aspose.PSD for Java API Reference
description: The bezier segment going from one point to the next point and using two control points.
type: docs
weight: 10
url: /java/com.aspose.psd.shapesegments/beziersegment/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ShapeSegment](../../com.aspose.psd/shapesegment), [com.aspose.psd.shapesegments.LineSegment](../../com.aspose.psd.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

The bezier segment going from one point to the next point and using two control points.
## Constructors

| Constructor | Description |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Initializes a new instance of the  BezierSegment  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Gets the ending point. |
| [getFirstControlPoint()](#getFirstControlPoint--) | Gets the first control point of a bezier spline. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Gets the second control point of a bezier spline. |
| [getStartPoint()](#getStartPoint--) | Gets the starting point. |
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


Initializes a new instance of the  BezierSegment  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.psd/pointf) | The start point. |
| firstControlPoint | [PointF](../../com.aspose.psd/pointf) | The first control point. |
| secondControlPoint | [PointF](../../com.aspose.psd/pointf) | The second control point. |
| endPoint | [PointF](../../com.aspose.psd/pointf) | The end point. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets the ending point.

Value: The ending point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Gets the first control point of a bezier spline.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Gets the second control point of a bezier spline.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The second control point.
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Gets the starting point.

Value: The starting point.

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

