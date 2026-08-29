---
title: "TiffStreamReader"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于处理小端 TIFF 文件格式的 TIFF 流。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

用于处理小端 TIFF 文件格式的 TIFF 流。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | 初始化 TiffStreamReader 类的新实例。 |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | 初始化 TiffStreamReader 类的新实例。 |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | 初始化 TiffStreamReader 类的新实例。 |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | 初始化 TiffStreamReader 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 获取读取器的长度。 |
| [getThrowExceptions()](#getThrowExceptions--) | 获取或设置一个值，指示在数据处理错误（读取或写入流）时是否抛出异常。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | 从流中读取 byte 值数组。 |
| [readBytes(long position, long count)](#readBytes-long-long-) | 从流中读取 unsigned byte 值数组。 |
| [readDouble(long position)](#readDouble-long-) | 从流中读取单个 double 值。 |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | 从流中读取 double 值数组。 |
| [readFloat(long position)](#readFloat-long-) | 从流中读取单个 float 值。 |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | 从流中读取 float 值数组。 |
| [readRational(long position)](#readRational-long-) | 从流中读取单个有理数值。 |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | 从流中读取有理数值数组。 |
| [readSByte(long position)](#readSByte-long-) | 从流中读取 signed byte 数据。 |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | 从流中读取 signed byte 值数组。 |
| [readSLong(long position)](#readSLong-long-) | 从流中读取 signed integer 值。 |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | 从流中读取 signed integer 值数组。 |
| [readSRational(long position)](#readSRational-long-) | 从流中读取单个 signed rational number 值。 |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | 从流中读取 signed rational 值数组。 |
| [readSShort(long position)](#readSShort-long-) | 从流中读取 signed short 值。 |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | 从流中读取有符号短整数数组。 |
| [readString_internalized(long position)](#readString-internalized-long-) | 从流中读取字符串。 |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | 从流中读取字符串。 |
| [readULong(long position)](#readULong-long-) | 从流中读取无符号整数值。 |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | 从流中读取无符号整数数组。 |
| [readUShort(long position)](#readUShort-long-) | 从流中读取无符号短整数值。 |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | 从流中读取无符号整数数组。 |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | 获取或设置一个值，指示在数据处理错误（读取或写入流）时是否抛出异常。 |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | 将底层数据转换为流容器。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


初始化 TiffStreamReader 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 字节数组数据。 |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


初始化 TiffStreamReader 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 字节数组数据。 |
| startIndex | int | 数据的起始索引。 |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


初始化 TiffStreamReader 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 字节数组数据。 |
| startIndex | int | 数据的起始索引。 |
| dataLength | int | 数据的长度。 |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


初始化 TiffStreamReader 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |

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
### getLength() {#getLength--}
```
public long getLength()
```


获取读取器的长度。

值：读取器长度。

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


获取或设置一个值，指示在数据处理错误（读取或写入流）时是否抛出异常。

值：如果在错误的数据处理时抛出异常则为 true；否则，错误情况将被静默忽略。

**Returns:**
boolean
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




### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


从流中读取 byte 值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| array | byte[] | 要填充的数组。 |
| arrayIndex | int | 开始放置值的数组索引。 |
| position | long | 要读取的流位置。 |
| count | long | 要读取的元素计数。 |

**Returns:**
long - 字节值数组。
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


从流中读取 unsigned byte 值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |
| count | long | 元素计数。 |

**Returns:**
byte[] - 无符号字节值数组。
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


从流中读取单个 double 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |

**Returns:**
double - 单个 double 值。
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


从流中读取 double 值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |
| count | long | 元素计数。 |

**Returns:**
double[] - double 值的数组。
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


从流中读取单个 float 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |

**Returns:**
float - 单个 float 值。
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


从流中读取 float 值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |
| count | long | 元素计数。 |

**Returns:**
float[] - float 值的数组。
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


从流中读取单个有理数值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


从流中读取有理数值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |
| count | long | 元素计数。 |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - 有理数值的数组。
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


从流中读取 signed byte 数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |

**Returns:**
byte - 有符号字节值。
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


从流中读取 signed byte 值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |
| count | long | 元素计数。 |

**Returns:**
byte[] - 有符号字节值的数组。
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


从流中读取 signed integer 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |

**Returns:**
int - 有符号整数值。
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


从流中读取 signed integer 值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |
| count | long | 元素计数。 |

**Returns:**
int[] - 有符号整数值的数组。
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


从流中读取单个 signed rational number 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


从流中读取 signed rational 值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |
| count | long | 元素计数。 |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - 有符号有理数值的数组。
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


从流中读取 signed short 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |

**Returns:**
short - 有符号 short 值。
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


从流中读取有符号短整数数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |
| count | long | 元素计数。 |

**Returns:**
short[] - 有符号 short 值的数组。
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


从流中读取字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 位置。 |

**Returns:**
java.lang.String - 字符串。
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


从流中读取字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 位置。 |
| 长度 | long | 长度。 |

**Returns:**
java.lang.String - 字符串。
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


从流中读取无符号整数值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |

**Returns:**
long - 无符号整数值。
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


从流中读取无符号整数数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |
| count | long | 元素计数。 |

**Returns:**
long[] - 无符号整数值的数组。
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


从流中读取无符号短整数值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |

**Returns:**
int - 无符号 short 值。
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


从流中读取无符号整数数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 读取位置。 |
| count | long | 元素计数。 |

**Returns:**
int[] - 无符号整数值的数组。
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


获取或设置一个值，指示在数据处理错误（读取或写入流）时是否抛出异常。

值：如果在错误的数据处理时抛出异常则为 true；否则，错误情况将被静默忽略。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


将底层数据转换为流容器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| startPosition | long | 开始转换的起始位置。 |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  with converted data.
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

