---
title: "TiffDataType"
second_title: "Aspose.PSD 的 Java API 参考"
description: "tiff 数据类型。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

tiff 数据类型。
## Methods

| Method | 描述 |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于该对象之前、之后，还是与其处于相同位置。 |
| [deepClone()](#deepClone--) | 对该实例执行深度克隆。 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | 获取以字节为单位的附加数据大小（如果 12 字节不足以容纳标签数据时）。 |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 获取元素的计数。 |
| [getDataSize()](#getDataSize--) | 获取以字节为单位的附加数据大小（如果 12 字节不足以容纳标签数据时）。 |
| [getId()](#getId--) | 获取标签 ID 的整数表示。 |
| [getTagId()](#getTagId--) | 获取标签 ID。 |
| [getTagType()](#getTagType--) | 获取标签类型。 |
| [getValue()](#getValue--) | 获取此数据类型包含的值。 |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | 获取一个值，指示标签是否为私有。 |
| [isValid()](#isValid--) | 获取一个值，指示标签数据是否有效。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | 读取标签数据。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 设置此数据类型包含的值。 |
| [toString()](#toString--) | 返回 一个  System.String  表示此实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | 写入附加标签数据。 |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | 写入标签数据。 |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于该对象之前、之后，还是与其处于相同位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 用于与此实例比较的对象。 |

**Returns:**
int - 一个 32 位有符号整数，指示被比较对象的相对顺序。返回值具有以下含义：值 含义 小于零 此实例小于 obj。 零 此实例等于 obj。 大于零 此实例大于 obj。
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


对该实例执行深度克隆。

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


获取以字节为单位的附加数据大小（如果 12 字节不足以容纳标签数据时）。

**Returns:**
long - 以字节为单位的附加数据大小。

这是对齐到字边界的数据字节计数。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


获取元素的计数。

**Returns:**
long - 元素的计数。
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


获取以字节为单位的附加数据大小（如果 12 字节不足以容纳标签数据时）。

**Returns:**
long - 以字节为单位的附加数据大小。

这是精确的字节计数。
### getId() {#getId--}
```
public int getId()
```


获取标签 ID 的整数表示。

**Returns:**
int - 标签 ID 的整数表示
### getTagId() {#getTagId--}
```
public int getTagId()
```


获取标签 ID。

**Returns:**
int - 标签 ID。
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


获取标签类型。

**Returns:**
int - 标签类型。
### getValue() {#getValue--}
```
public abstract Object getValue()
```


获取此数据类型包含的值。

**Returns:**
java.lang.Object - 值。
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


获取一个指示标签是否为私有的值。私有 TIFF 标签是标签 ID 大于 32768 的标签。

**Returns:**
boolean - 如果标签数据有效则为 true；否则为 false。
### isValid() {#isValid--}
```
public boolean isValid()
```


获取一个指示标签数据是否有效的值。有效的标签包含可以保留的数据。无效的标签无法存储。

**Returns:**
boolean - 如果标签数据有效则为 true；否则为 false。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


读取标签数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | 数据流。 |
| position | long | 标签位置。 |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


设置此数据类型包含的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object | 该值。 |

### toString() {#toString--}
```
public String toString()
```


返回 一个  System.String  表示此实例。

**Returns:**
java.lang.String - 一个  System.String  表示此实例。
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


写入附加标签数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | 数据流。 |

**Returns:**
long - 实际写入的字节数。
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


写入标签数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | 数据流。 |
| additionalDataOffset | long | 写入附加数据的偏移量。 |

