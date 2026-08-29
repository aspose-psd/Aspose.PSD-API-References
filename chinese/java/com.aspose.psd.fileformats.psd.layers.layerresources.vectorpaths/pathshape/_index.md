---
title: "PathShape"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Bezier 曲线节点构成的图形。"
type: docs
weight: 16
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

Bezier 曲线节点构成的图形。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PathShape()](#PathShape--) | 初始化 [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) 类的新实例。 |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | 初始化 [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | 获取贝塞尔节点数组。 |
| [getPathOperations()](#getPathOperations--) | 获取或设置路径操作（布尔操作）。 |
| [getShapeIndex()](#getShapeIndex--) | 获取或设置图层中当前路径形状的索引。 |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | 获取或设置一个值，指示此实例是否已关闭。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | 获取或设置一个值，指示此实例是否已关闭。 |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | 分配贝塞尔节点数组。 |
| [setPathOperations(int value)](#setPathOperations-int-) | 获取或设置路径操作（布尔操作）。 |
| [setShapeIndex(int value)](#setShapeIndex-int-) | 获取或设置图层中当前路径形状的索引。 |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | 基于此实例创建 VectorPathRecord 记录。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


初始化 [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) 类的新实例。

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


初始化 [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | 长度记录。 |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | 贝塞尔节点记录。 |

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


获取贝塞尔节点数组。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - BezierKnotRecord 数组
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


获取或设置路径操作（布尔操作）。

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


获取或设置图层中当前路径形状的索引。

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


获取或设置一个值，指示此实例是否已关闭。

值： true 如果此实例已关闭；否则， false 。

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


获取或设置一个值，指示此实例是否已关闭。

值： true 如果此实例已关闭；否则， false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


分配贝塞尔节点数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | 贝塞尔节点数组 |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


获取或设置路径操作（布尔操作）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


获取或设置图层中当前路径形状的索引。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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


基于此实例创建 VectorPathRecord 记录。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - 为此实例中的每个点返回一个 LengthRecord 和 BezierKnotRecord。
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

