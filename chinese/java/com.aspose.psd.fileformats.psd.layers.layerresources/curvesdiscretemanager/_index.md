---
title: "CurvesDiscreteManager"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于操作像素映射的曲线调整图层管理器"
type: docs
weight: 25
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

曲线调整图层的管理器，用于操作像素映射
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | 初始化 [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | 获取资源的字节。 |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | 获取用于处理过滤器的映射 |
| [getMaxChannelCount()](#getMaxChannelCount--) | 获取最大通道数。 |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | 获取指定位置的值。 |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | 从字节加载数据。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | 将指定位置设置为默认值。 |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | 在指定位置设置值。 |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | 设置整个通道的值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


初始化 [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| maxChannelCount | int | 最大通道数。 |

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
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


获取用于处理过滤器的映射

**Returns:**
byte[][] - 转换映射
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


获取最大通道数。

值：最大通道数。

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


获取指定位置的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| channelIndex | int | 通道索引。 |
| position | byte | 位置。 |

**Returns:**
byte - 曲线在其位置的值
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




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


将指定位置设置为默认值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| channelIndex | int | 通道索引。 |
| position | byte | 位置。 |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


在指定位置设置值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| channelIndex | int | 通道索引。 |
| position | byte | 位置。 |
| 值 | byte | 该值。 |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


设置整个通道的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| channelIndex | int | 通道索引。 |
| channelValue | byte[] | 通道值。 |

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

