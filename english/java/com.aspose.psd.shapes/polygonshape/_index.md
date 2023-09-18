---
title: PolygonShape
second_title: Aspose.PSD for Java API Reference
description: Represents a polygon shape.
type: docs
weight: 15
url: /java/com.aspose.psd.shapes/polygonshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Represents a polygon shape.
## Constructors

| Constructor | Description |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Initializes a new instance of the  PolygonShape  class. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.psd.PointF---) | Initializes a new instance of the  PolygonShape  class. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.psd.PointF---boolean-) | Initializes a new instance of the  PolygonShape  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Gets the object's bounds. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Gets the object's bounds. |
| [getCenter()](#getCenter--) | Gets the shape's center. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Gets the ending shape point. |
| [getPoints()](#getPoints--) | Gets or sets the curve points. |
| [getSegments()](#getSegments--) | Gets the shape segments. |
| [getStartPoint()](#getStartPoint--) | Gets the starting shape point. |
| [hasSegments()](#hasSegments--) | Gets a value indicating whether shape has segments. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Gets or sets a value indicating whether shape is closed. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Reverses the order of points for this shape. |
| [setClosed(boolean value)](#setClosed-boolean-) | Gets or sets a value indicating whether shape is closed. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Gets or sets the curve points. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applies the specified transformation to the shape. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Initializes a new instance of the  PolygonShape  class.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.psd.PointF---}
```
public PolygonShape(PointF[] points)
```


Initializes a new instance of the  PolygonShape  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | The points array. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.psd.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Initializes a new instance of the  PolygonShape  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | The points array. |
| isClosed | boolean | If set to  true  the polygon is closed. |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Gets the object's bounds.

Value: The object's bounds.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The matrix to apply before bounds will be calculated. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](../../com.aspose.psd/pen) | The pen to use for object. This can influence the object's bounds size. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Gets the shape's center.

Value: The shape's center.

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


Gets the ending shape point.

Value: The ending shape point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Gets or sets the curve points.

Value: The curve points.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gets the shape segments.

Value: The shape segments.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Gets the starting shape point.

Value: The starting shape point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Gets a value indicating whether shape has segments.

Value:  True  if shape has segments; otherwise,  false .

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


Gets or sets a value indicating whether shape is closed.

Value:  true  if shape is closed; otherwise,  false .

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


Reverses the order of points for this shape.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Gets or sets a value indicating whether shape is closed.

Value:  true  if shape is closed; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


Gets or sets the curve points.

Value: The curve points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

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


Applies the specified transformation to the shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | The transformation to apply. |

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

