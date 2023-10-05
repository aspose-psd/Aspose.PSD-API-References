---
title: CurvesDiscreteManager
second_title: Aspose.PSD for Java API Reference
description: Manager for Curves Adjustment Layer that manipulates pixels map
type: docs
weight: 23
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Manager for Curves Adjustment Layer that manipulates pixels' map
## Constructors

| Constructor | Description |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Initializes a new instance of the [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Gets the bytes for resource. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Gets the map for processing filter |
| [getMaxChannelCount()](#getMaxChannelCount--) | Gets the maximum channel count. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Gets the value in position. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Loads data from bytes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Sets to default value in position. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Sets the value in position. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Sets the value of whole channel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Initializes a new instance of the [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxChannelCount | int | The maximum channel count. |

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
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Gets the map for processing filter

**Returns:**
byte[][] - Transformation map
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Gets the maximum channel count.

Value: The maximum channel count.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Gets the value in position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |
| position | byte | The position. |

**Returns:**
byte - Value of curve by its position
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




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


Sets to default value in position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |
| position | byte | The position. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Sets the value in position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |
| position | byte | The position. |
| value | byte | The value. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Sets the value of whole channel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |
| channelValue | byte[] | The channel value. |

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

