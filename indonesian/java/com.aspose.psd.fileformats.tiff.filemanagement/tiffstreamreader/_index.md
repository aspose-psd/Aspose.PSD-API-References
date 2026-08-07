---
title: "TiffStreamReader"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Aliran tiff untuk menangani format file tiff little endian."
type: docs
weight: 10
url: /id/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

Aliran tiff untuk menangani format file tiff little endian.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Menginisialisasi sebuah instance baru dari kelas TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Menginisialisasi sebuah instance baru dari kelas TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Menginisialisasi sebuah instance baru dari kelas TiffStreamReader. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | Menginisialisasi sebuah instance baru dari kelas TiffStreamReader. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Mendapatkan panjang pembaca. |
| [getThrowExceptions()](#getThrowExceptions--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah pengecualian dilemparkan pada pemrosesan data yang salah (membaca atau menulis ke aliran). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Membaca sebuah array nilai byte dari aliran. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Membaca sebuah array nilai byte tak bertanda dari aliran. |
| [readDouble(long position)](#readDouble-long-) | Membaca satu nilai double dari aliran. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Membaca sebuah array nilai double dari aliran. |
| [readFloat(long position)](#readFloat-long-) | Membaca satu nilai float dari aliran. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Membaca sebuah array nilai float dari aliran. |
| [readRational(long position)](#readRational-long-) | Membaca satu nilai bilangan rasional dari aliran. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Membaca sebuah array nilai rasional dari aliran. |
| [readSByte(long position)](#readSByte-long-) | Membaca data byte bertanda dari aliran. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Membaca sebuah array nilai byte bertanda dari aliran. |
| [readSLong(long position)](#readSLong-long-) | Membaca nilai integer bertanda dari aliran. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | Membaca sebuah array nilai integer bertanda dari aliran. |
| [readSRational(long position)](#readSRational-long-) | Membaca satu nilai bilangan rasional bertanda dari aliran. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Membaca sebuah array nilai rasional bertanda dari aliran. |
| [readSShort(long position)](#readSShort-long-) | Membaca nilai short bertanda dari aliran. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Membaca sebuah array nilai short bertanda dari aliran. |
| [readString_internalized(long position)](#readString-internalized-long-) | Membaca string dari aliran. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | Membaca string dari aliran. |
| [readULong(long position)](#readULong-long-) | Baca nilai integer tak bertanda dari aliran. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Membaca sebuah array nilai integer tak bertanda dari aliran. |
| [readUShort(long position)](#readUShort-long-) | Baca nilai short tak bertanda dari aliran. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Membaca sebuah array nilai integer tak bertanda dari aliran. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah pengecualian dilemparkan pada pemrosesan data yang salah (membaca atau menulis ke aliran). |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Mengonversi data dasar ke kontainer aliran. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Menginisialisasi sebuah instance baru dari kelas TiffStreamReader.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data array byte. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Menginisialisasi sebuah instance baru dari kelas TiffStreamReader.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data array byte. |
| startIndex | int | Indeks awal ke data. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Menginisialisasi sebuah instance baru dari kelas TiffStreamReader.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data array byte. |
| startIndex | int | Indeks awal ke data. |
| dataLength | int | Panjang data. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Menginisialisasi sebuah instance baru dari kelas TiffStreamReader.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran. |

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
### getLength() {#getLength--}
```
public long getLength()
```


Mendapatkan panjang pembaca.

Nilai: Panjang pembaca.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah pengecualian dilemparkan pada pemrosesan data yang salah (membaca atau menulis ke aliran).

Nilai:  true  jika pengecualian dilemparkan pada pemrosesan data yang salah; jika tidak, kondisi kesalahan diabaikan secara diam-diam.

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


Membaca sebuah array nilai byte dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | byte[] | Array yang akan diisi. |
| arrayIndex | int | Indeks array untuk mulai menempatkan nilai. |
| position | long | Posisi aliran untuk dibaca. |
| count | long | Jumlah elemen yang akan dibaca. |

**Returns:**
long - Array nilai byte.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Membaca sebuah array nilai byte tak bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |
| count | long | Jumlah elemen. |

**Returns:**
byte[] - Array nilai byte tak bertanda.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Membaca satu nilai double dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |

**Returns:**
double - Nilai double tunggal.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Membaca sebuah array nilai double dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |
| count | long | Jumlah elemen. |

**Returns:**
double[] - Array nilai double.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Membaca satu nilai float dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |

**Returns:**
float - Nilai float tunggal.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Membaca sebuah array nilai float dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |
| count | long | Jumlah elemen. |

**Returns:**
float[] - Array nilai float.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Membaca satu nilai bilangan rasional dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Membaca sebuah array nilai rasional dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |
| count | long | Jumlah elemen. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Array nilai rasional.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Membaca data byte bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |

**Returns:**
byte - Nilai byte bertanda.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Membaca sebuah array nilai byte bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |
| count | long | Jumlah elemen. |

**Returns:**
byte[] - Array nilai byte bertanda.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


Membaca nilai integer bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |

**Returns:**
int - Nilai integer bertanda.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


Membaca sebuah array nilai integer bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |
| count | long | Jumlah elemen. |

**Returns:**
int[] - Array nilai integer bertanda.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Membaca satu nilai bilangan rasional bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Membaca sebuah array nilai rasional bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |
| count | long | Jumlah elemen. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - Array nilai rasional bertanda.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Membaca nilai short bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |

**Returns:**
short - Nilai short bertanda.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Membaca sebuah array nilai short bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |
| count | long | Jumlah elemen. |

**Returns:**
short[] - Array nilai short bertanda.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


Membaca string dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi. |

**Returns:**
java.lang.String - String.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


Membaca string dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi. |
| panjang | long | Panjang. |

**Returns:**
java.lang.String - String.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


Baca nilai integer tak bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |

**Returns:**
long - Nilai integer tak bertanda.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


Membaca sebuah array nilai integer tak bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |
| count | long | Jumlah elemen. |

**Returns:**
long[] - Array nilai integer tak bertanda.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Baca nilai short tak bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |

**Returns:**
int - Nilai short tak bertanda.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Membaca sebuah array nilai integer tak bertanda dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk dibaca. |
| count | long | Jumlah elemen. |

**Returns:**
int[] - Array nilai integer tak bertanda.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah pengecualian dilemparkan pada pemrosesan data yang salah (membaca atau menulis ke aliran).

Nilai:  true  jika pengecualian dilemparkan pada pemrosesan data yang salah; jika tidak, kondisi kesalahan diabaikan secara diam-diam.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Mengonversi data dasar ke kontainer aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startPosition | long | Posisi awal untuk memulai konversi dari. |

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

