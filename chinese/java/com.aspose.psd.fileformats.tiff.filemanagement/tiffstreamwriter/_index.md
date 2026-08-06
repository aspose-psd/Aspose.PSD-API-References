---
title: "TiffStreamWriter"
second_title: "Aspose.PSD 的 Java API 参考"
description: "TIFF 流写入器。"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

TIFF 流写入器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | 初始化 TiffStreamWriter 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | 获取或设置流的位置。 |
| [getSyncRoot()](#getSyncRoot--) | 获取一个可用于同步对同步资源访问的对象。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | 获取或设置流的位置。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | 写入指定的数据。 |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | 写入指定的数据。 |
| [writeDouble(double data)](#writeDouble-double-) | 向流写入单个 double 值。 |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | 向流写入 double 值数组。 |
| [writeFloat(float data)](#writeFloat-float-) | 向流写入单个 float 值。 |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | 向流写入 float 值数组。 |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | 向流写入单个有理数值。 |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | 向流写入无符号有理数值数组。 |
| [writeSByte(byte data)](#writeSByte-byte-) | 向流写入单个有符号字节值。 |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | 向流写入有符号字节值数组。 |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | 向流写入整数值数组。 |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | 将单个有符号有理数值写入流。 |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | 将有符号有理数值数组写入流。 |
| [writeSShort(short data)](#writeSShort-short-) | 将单个 short 值写入流。 |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | 将 short 值数组写入流。 |
| [writeSlong(int data)](#writeSlong-int-) | 将单个 integer 值写入流。 |
| [writeUByte(byte data)](#writeUByte-byte-) | 将单个 byte 值写入流。 |
| [writeULong(long data)](#writeULong-long-) | 将单个无符号 integer 值写入流。 |
| [writeULongArray(long[] data)](#writeULongArray-long---) | 将无符号 integer 值数组写入流。 |
| [writeUShort(int data)](#writeUShort-int-) | 将单个无符号 short 值写入流。 |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | 将无符号 short 值数组写入流。 |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


初始化 TiffStreamWriter 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流写入器。 |

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
### getPosition() {#getPosition--}
```
public long getPosition()
```


获取或设置流的位置。

值：流位置。

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取一个可用于同步对同步资源访问的对象。

值：可用于同步对已同步资源访问的对象。

**Returns:**
java.lang.Object
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




### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


获取或设置流的位置。

值：流位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

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

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


写入指定的数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 要写入的 data。 |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


写入指定的数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 要写入的 data。 |
| offset | int | data 偏移量。 |
| dataLength | int | 要写入的数据长度。 |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


向流写入单个 double 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | double | 要写入的值。 |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


向流写入 double 值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | double[] | 要写入的数组。 |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


向流写入单个 float 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | float | 要写入的值。 |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


向流写入 float 值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | float[] | 要写入的数组。 |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


向流写入单个有理数值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | 要写入的值。 |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


向流写入无符号有理数值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | 要写入的数组。 |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


向流写入单个有符号字节值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte | 要写入的值。 |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


向流写入有符号字节值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 要写入的数组。 |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


向流写入整数值数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | int[] | 要写入的数组。 |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


将单个有符号有理数值写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | 要写入的值。 |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


将有符号有理数值数组写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | 要写入的数组。 |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


将单个 short 值写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | short | 要写入的值。 |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


将 short 值数组写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | short[] | 要写入的数组。 |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


将单个 integer 值写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | int | 要写入的值。 |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


将单个 byte 值写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte | 要写入的值。 |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


将单个无符号 integer 值写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | long | 要写入的值。 |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


将无符号 integer 值数组写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | long[] | 要写入的数组。 |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


将单个无符号 short 值写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | int | 要写入的值。 |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


将无符号 short 值数组写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | int[] | 要写入的数组。 |

