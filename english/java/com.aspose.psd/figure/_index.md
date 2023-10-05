---
title: Figure
second_title: Aspose.PSD for Java API Reference
description: The figure.
type: docs
weight: 42
url: /java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

The figure. A container for shapes.
## Constructors

| Constructor | Description |
| --- | --- |
| [Figure()](#Figure--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Adds a shape to the figure. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Adds a range of shapes to the figure. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Gets or sets the object's bounds. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Gets the object's bounds. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Gets the whole figure segments. |
| [getShapes()](#getShapes--) | Gets the figure shapes. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Gets a value indicating whether this figure is closed. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Removes a shape from the figure. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Removes a range of shapes from the figure. |
| [reverse()](#reverse--) | Reverses this figure shapes order and shapes point order. |
| [setClosed(boolean value)](#setClosed-boolean-) | Sets a value indicating whether this figure is closed. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applies the specified transformation to the shape. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Figure() {#Figure--}
```
public Figure()
```


### addShape(Shape shape) {#addShape-com.aspose.psd.Shape-}
```
public void addShape(Shape shape)
```


Adds a shape to the figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | The shape to add. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Adds a range of shapes to the figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | The shapes to add. |

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


Gets or sets the object's bounds.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gets the whole figure segments.

**Returns:**
com.aspose.psd.ShapeSegment[] - The figure segments.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Gets the figure shapes.

**Returns:**
com.aspose.psd.Shape[] - The figure shapes.
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


Gets a value indicating whether this figure is closed. A closed figure will make a difference only in case where the first and the last figure's shapes are continuous shapes. In such case the first point of the first shape will be connected by a straight line from the last point of the last shape.

**Returns:**
boolean -  True  if this figure is closed; otherwise,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeShape(Shape shape) {#removeShape-com.aspose.psd.Shape-}
```
public void removeShape(Shape shape)
```


Removes a shape from the figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | The shape to remove. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Removes a range of shapes from the figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | The shapes range to remove. |

### reverse() {#reverse--}
```
public void reverse()
```


Reverses this figure shapes order and shapes point order.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Sets a value indicating whether this figure is closed. A closed figure will make a difference only in case where the first and the last figure's shapes are continuous shapes. In such case the first point of the first shape will be connected by a straight line from the last point of the last shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  True  if this figure is closed; otherwise,  false . |

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

