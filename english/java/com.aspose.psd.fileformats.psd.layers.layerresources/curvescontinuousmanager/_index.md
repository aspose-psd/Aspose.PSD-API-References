---
title: CurvesContinuousManager
second_title: Aspose.PSD for Java API Reference
description: Manager for Curves Adjustment Layer that manipulates curves
type: docs
weight: 24
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

Manager for Curves Adjustment Layer that manipulates curves
## Constructors

| Constructor | Description |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | Initializes a new instance of the [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) class. |
## Methods

| Method | Description |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | Adds the point of curve. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Gets the bytes for resource. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | Gets the curve point by index. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | Gets the curve point count. |
| [getMap_internalized()](#getMap-internalized--) | Gets the map for processing filter. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Gets the maximum channel count. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Loads data from bytes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | Removes the point of curve. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | Updates the point of curve. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


Initializes a new instance of the [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxChannelCount | int | The maximum channel count. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


Adds the point of curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |
| x | byte | The x location. |
| y | byte | The y location. |

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
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Gets the bytes for resource.

**Returns:**
byte[] - Bytes to compose CurvResource
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurvePointByIndex(int channelIndex, int pointIndex) {#getCurvePointByIndex-int-int-}
```
public final Point getCurvePointByIndex(int channelIndex, int pointIndex)
```


Gets the curve point by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |
| pointIndex | int | Index of the point. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


Gets the curve point count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |

**Returns:**
int - Count of Curve Point in channel
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Gets the map for processing filter.

**Returns:**
byte[][] - Map for channel processing.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Gets the maximum channel count.

Value: The maximum channel count.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadFromBytes_internalized(byte[] bytes) {#loadFromBytes-internalized-byte---}
```
public void loadFromBytes_internalized(byte[] bytes)
```


Loads data from bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | byte[] | The bytes. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeCurvePoint(int channelIndex, int pointIndex) {#removeCurvePoint-int-int-}
```
public final void removeCurvePoint(int channelIndex, int pointIndex)
```


Removes the point of curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |
| pointIndex | int | Index of the point. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y) {#updateCurvePoint-int-int-byte-byte-}
```
public final void updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)
```


Updates the point of curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |
| pointIndex | int | Index of the point. |
| x | byte | The x location. |
| y | byte | The y location. |

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

