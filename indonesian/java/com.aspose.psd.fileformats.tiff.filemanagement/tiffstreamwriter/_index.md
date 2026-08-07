---
title: "TiffStreamWriter"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Penulis aliran Tiff."
type: docs
weight: 11
url: /id/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

Penulis aliran Tiff.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | Menginisialisasi instance baru dari kelas TiffStreamWriter. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | Mendapatkan atau mengatur posisi aliran. |
| [getSyncRoot()](#getSyncRoot--) | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | Mendapatkan atau mengatur posisi aliran. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | Menulis data yang ditentukan. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Menulis data yang ditentukan. |
| [writeDouble(double data)](#writeDouble-double-) | Menulis satu nilai double ke aliran. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Menulis array nilai double ke aliran. |
| [writeFloat(float data)](#writeFloat-float-) | Menulis satu nilai float ke aliran. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Menulis array nilai float ke aliran. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | Menulis satu nilai bilangan rasional ke aliran. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | Menulis array nilai rasional tak bertanda ke aliran. |
| [writeSByte(byte data)](#writeSByte-byte-) | Menulis satu nilai byte bertanda ke aliran. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Menulis array nilai byte bertanda ke aliran. |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | Menulis array nilai integer ke aliran. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | Menulis satu nilai bilangan rasional bertanda ke aliran. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | Menulis sebuah array nilai bilangan rasional bertanda ke aliran. |
| [writeSShort(short data)](#writeSShort-short-) | Menulis satu nilai short ke aliran. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Menulis sebuah array nilai short ke aliran. |
| [writeSlong(int data)](#writeSlong-int-) | Menulis satu nilai integer ke aliran. |
| [writeUByte(byte data)](#writeUByte-byte-) | Menulis satu nilai byte ke aliran. |
| [writeULong(long data)](#writeULong-long-) | Menulis satu nilai unsigned integer ke aliran. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Menulis sebuah array nilai unsigned integer ke aliran. |
| [writeUShort(int data)](#writeUShort-int-) | Menulis satu nilai unsigned short ke aliran. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Menulis sebuah array nilai unsigned short ke aliran. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Menginisialisasi instance baru dari kelas TiffStreamWriter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Penulis aliran. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mendapatkan atau mengatur posisi aliran.

Nilai: Posisi aliran.

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan.

Nilai: Objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan.

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


Mendapatkan atau mengatur posisi aliran.

Nilai: Posisi aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Menulis data yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data yang akan ditulis. |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Menulis data yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data yang akan ditulis. |
| offset | int | Offset data. |
| dataLength | int | Panjang data untuk ditulis. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Menulis satu nilai double ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | double | Nilai yang akan ditulis. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Menulis array nilai double ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | double[] | Array yang akan ditulis. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Menulis satu nilai float ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | float | Nilai yang akan ditulis. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Menulis array nilai float ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | float[] | Array yang akan ditulis. |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Menulis satu nilai bilangan rasional ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Nilai yang akan ditulis. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Menulis array nilai rasional tak bertanda ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | Array yang akan ditulis. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Menulis satu nilai byte bertanda ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte | Nilai yang akan ditulis. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Menulis array nilai byte bertanda ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Array yang akan ditulis. |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


Menulis array nilai integer ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | int[] | Array yang akan ditulis. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Menulis satu nilai bilangan rasional bertanda ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | Nilai yang akan ditulis. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Menulis sebuah array nilai bilangan rasional bertanda ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | Array yang akan ditulis. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Menulis satu nilai short ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | short | Nilai yang akan ditulis. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Menulis sebuah array nilai short ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | short[] | Array yang akan ditulis. |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


Menulis satu nilai integer ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | int | Nilai yang akan ditulis. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Menulis satu nilai byte ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte | Nilai yang akan ditulis. |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


Menulis satu nilai unsigned integer ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | long | Nilai yang akan ditulis. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


Menulis sebuah array nilai unsigned integer ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | long[] | Array yang akan ditulis. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Menulis satu nilai unsigned short ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | int | Nilai yang akan ditulis. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Menulis sebuah array nilai unsigned short ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | int[] | Array yang akan ditulis. |

