---
title: TiffStreamWriter
second_title: Aspose.PSD for Java API Reference
description: Tiff stream writer.
type: docs
weight: 11
url: /java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

Tiff stream writer.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | Initializes a new instance of the  TiffStreamWriter  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | Gets or sets the stream position. |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the synchronized resource. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | Gets or sets the stream position. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | Writes the specified data. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Writes the specified data. |
| [writeDouble(double data)](#writeDouble-double-) | Writes a single double value to the stream. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Writes an array of double values to the stream. |
| [writeFloat(float data)](#writeFloat-float-) | Writes a single float value to the stream. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Writes an array of float values to the stream. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | Writes a single rational number value to the stream. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | Writes an array of unsigned rational values to the stream. |
| [writeSByte(byte data)](#writeSByte-byte-) | Writes a single signed byte value to the stream. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Writes an array of signed byte values to the stream. |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | Writes an array of integer values to the stream. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | Writes a single signed rational number value to the stream. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | Writes an array of signed rational values to the stream. |
| [writeSShort(short data)](#writeSShort-short-) | Writes a single short value to the stream. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Writes an array of short values to the stream. |
| [writeSlong(int data)](#writeSlong-int-) | Writes a single integer value to the stream. |
| [writeUByte(byte data)](#writeUByte-byte-) | Writes a single byte value to the stream. |
| [writeULong(long data)](#writeULong-long-) | Writes a single unsigned integer value to the stream. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Writes an array of unsigned integer values to the stream. |
| [writeUShort(int data)](#writeUShort-int-) | Writes a single unsigned short value to the stream. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Writes an array of unsigned short values to the stream. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Initializes a new instance of the  TiffStreamWriter  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream writer. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets or sets the stream position.

Value: The stream position.

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the synchronized resource.

Value: The object that can be used to synchronize access to the synchronized resource.

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


Gets or sets the stream position.

Value: The stream position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Writes the specified data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The data to write. |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Writes the specified data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The data to write. |
| offset | int | The data offset. |
| dataLength | int | Length of the data to writer. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Writes a single double value to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | double | The value to write. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Writes an array of double values to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | double[] | The array to write. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Writes a single float value to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | float | The value to write. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Writes an array of float values to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | float[] | The array to write. |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Writes a single rational number value to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | The value to write. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Writes an array of unsigned rational values to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | The array to write. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Writes a single signed byte value to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte | The value to write. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Writes an array of signed byte values to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The array to write. |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


Writes an array of integer values to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | int[] | The array to write. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Writes a single signed rational number value to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | The value to write. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Writes an array of signed rational values to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | The array to write. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Writes a single short value to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | short | The value to write. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Writes an array of short values to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | short[] | The array to write. |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


Writes a single integer value to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | int | The value to write. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Writes a single byte value to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte | The value to write. |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


Writes a single unsigned integer value to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | long | The value to write. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


Writes an array of unsigned integer values to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | long[] | The array to write. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Writes a single unsigned short value to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | int | The value to write. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Writes an array of unsigned short values to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | int[] | The array to write. |

