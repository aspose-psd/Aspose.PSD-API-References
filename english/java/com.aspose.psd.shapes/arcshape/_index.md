---
title: ArcShape
second_title: Aspose.PSD for Java API Reference
description: Represents an arc shape.
type: docs
weight: 10
url: /java/com.aspose.psd.shapes/arcshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape), [com.aspose.psd.shapes.PieShape](../../com.aspose.psd.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Represents an arc shape.
## Constructors

| Constructor | Description |
| --- | --- |
| [ArcShape()](#ArcShape--) | Initializes a new instance of the  ArcShape  class. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.psd.RectangleF-float-float-) | Initializes a new instance of the  ArcShape  class. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-) | Initializes a new instance of the  ArcShape  class. |
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
| [getLeftBottom()](#getLeftBottom--) | Gets the left bottom rectangle point. |
| [getLeftTop()](#getLeftTop--) | Gets the left top rectangle point. |
| [getRectangleHeight()](#getRectangleHeight--) | Gets the rectangle height. |
| [getRectangleWidth()](#getRectangleWidth--) | Gets the rectangle width. |
| [getRightBottom()](#getRightBottom--) | Gets the right bottom rectangle point. |
| [getRightTop()](#getRightTop--) | Gets the right top rectangle point. |
| [getSegments()](#getSegments--) | Gets the shape segments. |
| [getStartAngle()](#getStartAngle--) | Gets or sets the start angle. |
| [getStartPoint()](#getStartPoint--) | Gets the starting shape point. |
| [getSweepAngle()](#getSweepAngle--) | Gets or sets the sweep angle. |
| [hasSegments()](#hasSegments--) | Gets a value indicating whether shape has segments. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Gets or sets a value indicating whether ordered shape is closed. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Reverses the order of points for this shape. |
| [setClosed(boolean value)](#setClosed-boolean-) | Gets or sets a value indicating whether ordered shape is closed. |
| [setStartAngle(float value)](#setStartAngle-float-) | Gets or sets the start angle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Gets or sets the sweep angle. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applies the specified transformation to the shape. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Initializes a new instance of the  ArcShape  class.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.psd.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Initializes a new instance of the  ArcShape  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | The rectangle. |
| startAngle | float | The start angle. |
| sweepAngle | float | The sweep angle. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Initializes a new instance of the  ArcShape  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | The rectangle. |
| startAngle | float | The start angle. |
| sweepAngle | float | The sweep angle. |
| isClosed | boolean | If set to  true  the arc is closed. The closed arc is actually degenereates to an ellipse. |

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
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Gets the left bottom rectangle point.

Value: The left bottom rectangle point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Gets the left top rectangle point.

Value: The left top rectangle point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Gets the rectangle height.

Value: The rectangle height.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Gets the rectangle width.

Value: The rectangle width.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Gets the right bottom rectangle point.

Value: The right bottom rectangle point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Gets the right top rectangle point.

Value: The right top rectangle point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gets the shape segments.

Value: The shape segments.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Gets or sets the start angle.

Value: The start angle.

**Returns:**
float
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Gets the starting shape point.

Value: The starting shape point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Gets or sets the sweep angle.

Value: The sweep angle.

**Returns:**
float
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


Gets or sets a value indicating whether ordered shape is closed. When processing closed ordered shape the starting and ending points have no meaning.

Value:  True  if this ordered shape is closed; otherwise,  false .

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


Gets or sets a value indicating whether ordered shape is closed. When processing closed ordered shape the starting and ending points have no meaning.

Value:  True  if this ordered shape is closed; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Gets or sets the start angle.

Value: The start angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Gets or sets the sweep angle.

Value: The sweep angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

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

