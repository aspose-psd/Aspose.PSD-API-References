---
title: PieShape
second_title: Aspose.PSD for Java API Reference
description: Represents a pie shape.
type: docs
weight: 14
url: /java/com.aspose.psd.shapes/pieshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape)
```
public class PieShape extends EllipseShape
```

Represents a pie shape.
## Constructors

| Constructor | Description |
| --- | --- |
| [PieShape()](#PieShape--) | Initializes a new instance of the  PieShape  class. |
| [PieShape(RectangleF rectangle, float startAngle, float sweepAngle)](#PieShape-com.aspose.psd.RectangleF-float-float-) | Initializes a new instance of the  PieShape  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Gets the object's bounds. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Gets the object's bounds. |
| [getCenter()](#getCenter--) | Gets the shape's center. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Gets the left bottom rectangle point. |
| [getLeftTop()](#getLeftTop--) | Gets the left top rectangle point. |
| [getRectangleHeight()](#getRectangleHeight--) | Gets the rectangle height. |
| [getRectangleWidth()](#getRectangleWidth--) | Gets the rectangle width. |
| [getRightBottom()](#getRightBottom--) | Gets the right bottom rectangle point. |
| [getRightTop()](#getRightTop--) | Gets the right top rectangle point. |
| [getSegments()](#getSegments--) | Gets the shape segments. |
| [getStartAngle()](#getStartAngle--) | Gets or sets the start angle. |
| [getSweepAngle()](#getSweepAngle--) | Gets or sets the sweep angle. |
| [hasSegments()](#hasSegments--) | Gets a value indicating whether shape has segments. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setStartAngle(float value)](#setStartAngle-float-) | Gets or sets the start angle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Gets or sets the sweep angle. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applies the specified transformation to the shape. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PieShape() {#PieShape--}
```
public PieShape()
```


Initializes a new instance of the  PieShape  class.

### PieShape(RectangleF rectangle, float startAngle, float sweepAngle) {#PieShape-com.aspose.psd.RectangleF-float-float-}
```
public PieShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Initializes a new instance of the  PieShape  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | The rectangle. |
| startAngle | float | The start angle. |
| sweepAngle | float | The sweep angle. |

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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

