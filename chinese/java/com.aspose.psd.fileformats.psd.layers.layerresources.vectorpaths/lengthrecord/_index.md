---
title: "LengthRecord"
second_title: "Aspose.PSD 的 Java API 参考"
description: "子路径长度记录类"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

子路径长度记录类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | 初始化一个新的 [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) 类的实例。 |
| [LengthRecord()](#LengthRecord--) | 初始化一个新的 [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) 类的实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | 获取或设置贝塞尔节点记录的计数。 |
| [getClass()](#getClass--) |  |
| [getLength_internalized()](#getLength-internalized--) | 获取长度。 |
| [getPathOperations()](#getPathOperations--) | 获取或设置路径操作。 |
| [getRecordCount()](#getRecordCount--) | 获取或设置记录计数。 |
| [getShapeIndex()](#getShapeIndex--) | 获取或设置图层中当前路径形状的索引。 |
| [getSourceData_internalized()](#getSourceData-internalized--) | 获取原始源数据字节。 |
| [getType()](#getType--) | 获取类型。 |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | 获取或设置一个值，指示此实例是否已关闭。 |
| [isOpen()](#isOpen--) | 获取或设置一个值，指示此实例是否已打开。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | 获取或设置贝塞尔节点记录的计数。 |
| [setClosed(boolean value)](#setClosed-boolean-) | 获取或设置一个值，指示此实例是否已关闭。 |
| [setOpen(boolean value)](#setOpen-boolean-) | 获取或设置一个值，指示此实例是否已打开。 |
| [setPathOperations(int value)](#setPathOperations-int-) | 获取或设置路径操作。 |
| [setRecordCount(int value)](#setRecordCount-int-) | 获取或设置记录计数。 |
| [setShapeIndex(int value)](#setShapeIndex-int-) | 获取或设置图层中当前路径形状的索引。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


初始化一个新的 [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) 类的实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 记录数据。 |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


初始化一个新的 [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) 类的实例。

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
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


获取或设置贝塞尔节点记录的计数。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength_internalized() {#getLength-internalized--}
```
public final int getLength_internalized()
```


获取长度。

值：长度。

**Returns:**
int
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


获取或设置路径操作。

**Returns:**
int
### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


获取或设置记录计数。

值：记录计数。

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


获取或设置图层中当前路径形状的索引。

**Returns:**
int
### getSourceData_internalized() {#getSourceData-internalized--}
```
public final byte[] getSourceData_internalized()
```


获取原始源数据字节。

**Returns:**
byte[] - 字节数组。
### getType() {#getType--}
```
public short getType()
```


获取类型。

值：类型。

**Returns:**
short
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
### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


获取或设置一个值，指示此实例是否已打开。

值：如果此实例已打开则为 true；否则为 false。

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




### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


获取或设置贝塞尔节点记录的计数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


获取或设置一个值，指示此实例是否已打开。

值：如果此实例已打开则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


获取或设置路径操作。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


获取或设置记录计数。

值：记录计数。

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

