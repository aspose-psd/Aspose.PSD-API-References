---
title: "ClassID"
second_title: "Aspose.PSD 的 Java API 参考"
description: "PSD 类 ID 对象。"
type: docs
weight: 19
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/classid/
---

**Inheritance:**
java.lang.Object
```
public class ClassID
```

PSD 类 ID 对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ClassID(byte[] classID)](#ClassID-byte---) | 初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。 |
| [ClassID(byte[] classID, boolean isZeroLength)](#ClassID-byte---boolean-) | 初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。 |
| [ClassID(int classID)](#ClassID-int-) | 初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。 |
| [ClassID(long classID)](#ClassID-long-) | 初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。 |
| [ClassID(String classID, boolean isZeroLength)](#ClassID-java.lang.String-boolean-) | 初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。 |
| [ClassID(String classID)](#ClassID-java.lang.String-) | 初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytes()](#getBytes--) | 获取表示 class ID 的字节。 |
| [getClass()](#getClass--) |  |
| [getClassName()](#getClassName--) | 获取类名的 ASCII 编码。 |
| [getEmpty_internalized()](#getEmpty-internalized--) | 获取具有 '\\0' 值的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类型的新实例。 |
| [getLength()](#getLength--) | 获取 class ID 的字节长度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | 将类信息保存到指定的流容器。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ClassID(byte[] classID) {#ClassID-byte---}
```
public ClassID(byte[] classID)
```


初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| classID | byte[] | class ID 作为字节序列。 |

### ClassID(byte[] classID, boolean isZeroLength) {#ClassID-byte---boolean-}
```
public ClassID(byte[] classID, boolean isZeroLength)
```


初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| classID | byte[] | class ID 作为字节序列。 |
| isZeroLength | boolean | 如果设置为 true [is zero length]。记录的字符串长度为零，但实际为四。 |

### ClassID(int classID) {#ClassID-int-}
```
public ClassID(int classID)
```


初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| classID | int | 类 ID。 |

### ClassID(long classID) {#ClassID-long-}
```
public ClassID(long classID)
```


初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| classID | long | 类 ID。 |

### ClassID(String classID, boolean isZeroLength) {#ClassID-java.lang.String-boolean-}
```
public ClassID(String classID, boolean isZeroLength)
```


初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| classID | java.lang.String | class ID 的 ASCII 编码。 |
| isZeroLength | boolean | 如果设置为 true [is zero length]。 |

### ClassID(String classID) {#ClassID-java.lang.String-}
```
public ClassID(String classID)
```


初始化一个新的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| classID | java.lang.String | class ID 的 ASCII 编码。 |

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
### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


获取表示 class ID 的字节。

**Returns:**
byte[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassName() {#getClassName--}
```
public final String getClassName()
```


获取类名的 ASCII 编码。

值：类名。

**Returns:**
java.lang.String
### getEmpty_internalized() {#getEmpty-internalized--}
```
public static ClassID getEmpty_internalized()
```


获取具有 '\\0' 值的 [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) 类型的新实例。

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) - The new instance of [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) type with '\\0' value.
### getLength() {#getLength--}
```
public final int getLength()
```


获取 class ID 的字节长度。

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




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


将类信息保存到指定的流容器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要保存到的流容器。 |

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

