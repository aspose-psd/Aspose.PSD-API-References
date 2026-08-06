---
title: "VectorPathData"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于处理矢量路径的类。"
type: docs
weight: 18
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

用于处理矢量路径的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | 初始化 [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) 类的新实例。 |
| [VectorPathData()](#VectorPathData--) | 初始化 [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | 通用信息（如版本和标志）的大小。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | 获取为字节数组。 |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 获取资源中向量路径数据的长度（字节）。 |
| [getPaths()](#getPaths--) | 获取或设置路径记录。 |
| [getVersion()](#getVersion--) | 获取或设置版本。 |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | 获取或设置一个值，以指示此实例是否已禁用。 |
| [isInverted()](#isInverted--) | 获取或设置一个值，以指示此实例是否已反转。 |
| [isNotLinked()](#isNotLinked--) | 获取或设置一个值，以指示此实例是否未链接。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | 获取或设置一个值，以指示此实例是否已禁用。 |
| [setInverted(boolean value)](#setInverted-boolean-) | 获取或设置一个值，以指示此实例是否已反转。 |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | 获取或设置一个值，以指示此实例是否未链接。 |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | 获取或设置路径记录。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置版本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


初始化 [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 资源数据。 |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


初始化 [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) 类的新实例。

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


通用信息（如版本和标志）的大小。

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


获取为字节数组。

**Returns:**
byte[] - 资源的字节数组。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


获取资源中向量路径数据的长度（字节）。

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


获取或设置路径记录。

Value: 路径。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


获取或设置版本。

值：版本。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


获取或设置一个值，以指示此实例是否已禁用。

Value:  true  如果此实例已禁用；否则为  false 。

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


获取或设置一个值，以指示此实例是否已反转。

Value:  true  如果此实例已反转；否则为  false 。

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


获取或设置一个值，以指示此实例是否未链接。

Value:  true  如果此实例未链接；否则为  false 。

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




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


获取或设置一个值，以指示此实例是否已禁用。

Value:  true  如果此实例已禁用；否则为  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


获取或设置一个值，以指示此实例是否已反转。

Value:  true  如果此实例已反转；否则为  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


获取或设置一个值，以指示此实例是否未链接。

Value:  true  如果此实例未链接；否则为  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


获取或设置路径记录。

Value: 路径。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


获取或设置版本。

值：版本。

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

