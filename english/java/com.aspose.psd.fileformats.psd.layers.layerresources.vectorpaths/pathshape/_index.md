---
title: PathShape
second_title: Aspose.PSD for Java API Reference
description: The figure from the knots of the Bezier curve.
type: docs
weight: 16
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

The figure from the knots of the Bezier curve.
## Constructors

| Constructor | Description |
| --- | --- |
| [PathShape()](#PathShape--) | Initializes a new instance of the [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) class. |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Initializes a new instance of the [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | Gets array of Bezier knots. |
| [getPathOperations()](#getPathOperations--) | Gets or sets the path operations (Boolean operations). |
| [getShapeIndex()](#getShapeIndex--) | Gets or sets the index of current path shape in layer. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Gets or sets a value indicating whether this instance is closed. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | Gets or sets a value indicating whether this instance is closed. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Assignes array of Bexier knots. |
| [setPathOperations(int value)](#setPathOperations-int-) | Gets or sets the path operations (Boolean operations). |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Gets or sets the index of current path shape in layer. |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | Creates the  VectorPathRecord  records based on this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


Initializes a new instance of the [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) class.

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


Initializes a new instance of the [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | The length record. |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | The bezier knot records. |

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
### getItems() {#getItems--}
```
public final BezierKnotRecord[] getItems()
```


Gets array of Bezier knots.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Array of BezierKnotRecord
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Gets or sets the path operations (Boolean operations).

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Gets or sets the index of current path shape in layer.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Gets or sets a value indicating whether this instance is closed.

Value:  true  if this instance is closed; otherwise,  false .

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




### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Gets or sets a value indicating whether this instance is closed.

Value:  true  if this instance is closed; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


Assignes array of Bexier knots.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Array of bezier knots |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Gets or sets the path operations (Boolean operations).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Gets or sets the index of current path shape in layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toVectorPathRecords() {#toVectorPathRecords--}
```
public final System.Collections.Generic.IGenericEnumerable<VectorPathRecord> toVectorPathRecords()
```


Creates the  VectorPathRecord  records based on this instance.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - Returns one  LengthRecord  and  BezierKnotRecord  for each point in this instance.
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

