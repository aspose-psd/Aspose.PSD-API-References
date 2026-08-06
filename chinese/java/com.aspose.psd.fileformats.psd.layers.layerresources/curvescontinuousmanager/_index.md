---
title: "CurvesContinuousManager"
second_title: "Aspose.PSD 的 Java API 参考"
description: "曲线调整图层的管理器，用于操作曲线"
type: docs
weight: 24
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

曲线调整图层的管理器，用于操作曲线
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | 初始化 [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | 添加曲线点。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | 获取资源的字节。 |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | 按索引获取曲线点。 |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | 获取曲线点的数量。 |
| [getMap_internalized()](#getMap-internalized--) | 获取用于处理过滤器的映射。 |
| [getMaxChannelCount()](#getMaxChannelCount--) | 获取最大通道数。 |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | 从字节加载数据。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | 移除曲线点。 |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | 更新曲线点。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


初始化 [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| maxChannelCount | int | 最大通道数。 |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


添加曲线点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| channelIndex | int | 通道索引。 |
| x | byte | x 位置。 |
| y | byte | y 位置。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


获取资源的字节。

**Returns:**
byte[] - 用于组成 CurvResource 的字节
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


按索引获取曲线点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| channelIndex | int | 通道索引。 |
| pointIndex | int | 点的索引。 |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


获取曲线点的数量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| channelIndex | int | 通道索引。 |

**Returns:**
int - 通道中曲线点的计数
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


获取用于处理过滤器的映射。

**Returns:**
byte[][] - 用于通道处理的映射。
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


获取最大通道数。

值：最大通道数。

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


从字节加载数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 字节 | byte[] | 字节。 |

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


移除曲线点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| channelIndex | int | 通道索引。 |
| pointIndex | int | 点的索引。 |

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


更新曲线点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| channelIndex | int | 通道索引。 |
| pointIndex | int | 点的索引。 |
| x | byte | x 位置。 |
| y | byte | y 位置。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

