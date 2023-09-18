---
title: IPathShape
second_title: Aspose.PSD for Java API Reference
description: The Shape from the knots of the Bezier curve.
type: docs
weight: 31
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

The Shape from the knots of the Bezier curve.
## Methods

| Method | Description |
| --- | --- |
| [getItems()](#getItems--) | Gets array of Bezier knots. |
| [getPathOperations()](#getPathOperations--) | The operations for the path shapes combining (Boolean operations). |
| [isClosed()](#isClosed--) | Gets or sets property that determines if Shape is closed. |
| [setClosed(boolean value)](#setClosed-boolean-) | Gets or sets property that determines if Shape is closed. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Assignes array of Bexier knots. |
| [setPathOperations(int value)](#setPathOperations-int-) | The operations for the path shapes combining (Boolean operations). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Gets array of Bezier knots.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Array of BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


The operations for the path shapes combining (Boolean operations).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Gets or sets property that determines if Shape is closed.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Gets or sets property that determines if Shape is closed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Assignes array of Bexier knots.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Array of bezier knots |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


The operations for the path shapes combining (Boolean operations).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

