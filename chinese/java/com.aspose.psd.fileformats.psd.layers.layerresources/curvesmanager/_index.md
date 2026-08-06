---
title: "CurvesManager"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于管理 CurvResource 的基类"
type: docs
weight: 26
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class CurvesManager
```

用于管理 CurvResource 的基类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CurvesManager(int maxChannelCount)](#CurvesManager-int-) | 初始化 [CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | 获取资源的字节。 |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | 获取用于处理过滤器的映射 |
| [getMaxChannelCount()](#getMaxChannelCount--) | 获取最大通道数。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesManager(int maxChannelCount) {#CurvesManager-int-}
```
public CurvesManager(int maxChannelCount)
```


初始化 [CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) 类的新实例。

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
public abstract byte[][] getMap_internalized()
```


获取用于处理过滤器的映射

**Returns:**
byte[][] - 通道处理的映射
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

