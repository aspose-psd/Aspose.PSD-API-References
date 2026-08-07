---
title: "SplitStreamContainer"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili kontainer aliran terpisah yang berisi aliran dan menyediakan rutin pemrosesan aliran."
type: docs
weight: 102
url: /id/java/com.aspose.psd/splitstreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Mewakili kontainer aliran terpisah yang berisi aliran dan menyediakan rutin pemrosesan aliran.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Menginisialisasi sebuah instance baru dari kelas [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Menginisialisasi sebuah instance baru dari kelas [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-) | Menginisialisasi sebuah instance baru dari kelas [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Menentukan jumlah byte baca dan tulis saat membaca secara berurutan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [canRead()](#canRead--) | Menampilkan nilai yang menunjukkan apakah aliran mendukung pembacaan. |
| [canSeek()](#canSeek--) | Menampilkan nilai yang menunjukkan apakah aliran mendukung pencarian. |
| [canWrite()](#canWrite--) | Menampilkan nilai yang menunjukkan apakah aliran mendukung penulisan. |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Menghapus semua buffer untuk aliran ini dan menyebabkan data yang di-buffer ditulis ke perangkat dasar. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getLength()](#getLength--) | Menampilkan atau mengatur panjang aliran dalam byte. |
| [getPosition()](#getPosition--) | Menampilkan atau mengatur posisi saat ini dalam aliran. |
| [getStream()](#getStream--) | Menampilkan aliran data. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan. |
| [hashCode()](#hashCode--) |  |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.psd.StreamContainer-boolean-) | Menyisipkan kontainer aliran ke posisi yang ditentukan. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Menampilkan nilai yang menunjukkan apakah aliran ini dibuang saat ditutup. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | Membaca byte untuk mengisi buffer byte yang ditentukan. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebanyak jumlah byte yang dibaca. |
| [readByte()](#readByte--) | Membaca satu byte dari aliran dan memajukan posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Menyimpan (menyalin) semua data aliran ke aliran yang ditentukan. |
| [save(OutputStream dstStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [save(String filePath)](#save-java.lang.String-) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)](#save-internalized-com.aspose.ms.System.IO.Stream-int-long-) |  |
| [seek(long offset, int origin)](#seek-long-int-) | Mengatur posisi dalam aliran saat ini. |
| [seekBegin()](#seekBegin--) | Mengatur posisi aliran ke awal aliran. |
| [setLength(long value)](#setLength-long-) | Menampilkan atau mengatur panjang aliran dalam byte. |
| [setPosition(long value)](#setPosition-long-) | Menampilkan atau mengatur posisi saat ini dalam aliran. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Mengonversi data aliran menjadi array  byte . |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Mengonversi data aliran menjadi array  byte . |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Melakukan konversi eksplisit dari  com.aspose.imaging.StreamContainer  ke  System.IO.Stream . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Menulis semua byte yang ditentukan ke aliran. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini sebanyak jumlah byte yang ditulis. |
| [writeByte(byte value)](#writeByte-byte-) | Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran satu byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Mengopi data yang terkandung ke StreamContainer lain . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Mengopi data yang terkandung ke StreamContainer lain . |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Menginisialisasi sebuah instance baru dari kelas [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Menginisialisasi sebuah instance baru dari kelas [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran data. |
| disposeStream | boolean | jika diatur ke  true  aliran akan dibuang ketika kontainer dibuang. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Menginisialisasi sebuah instance baru dari kelas [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran. |
| disposeStream | boolean | jika diatur ke  true  menutup stream. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Menentukan jumlah byte baca dan tulis saat membaca secara berurutan.

### canRead() {#canRead--}
```
public boolean canRead()
```


Menampilkan nilai yang menunjukkan apakah aliran mendukung pembacaan.

Nilai:  true  jika stream mendukung pembacaan; jika tidak,  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Menampilkan nilai yang menunjukkan apakah aliran mendukung pencarian.

Nilai:  true  jika stream mendukung pencarian; jika tidak,  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Menampilkan nilai yang menunjukkan apakah aliran mendukung penulisan.

Nilai:  true  jika stream mendukung penulisan; jika tidak,  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. Metode ini hanya memanggil metode dispose.

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| startPosition | long |  |
| disposeStream | boolean |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### dispose() {#dispose--}
```
public final void dispose()
```


Membuang instance saat ini.

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
### flush() {#flush--}
```
public void flush()
```


Menghapus semua buffer untuk aliran ini dan menyebabkan data yang di-buffer ditulis ke perangkat dasar.

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang.

**Returns:**
boolean - true jika dibuang; jika tidak, false.
### getLength() {#getLength--}
```
public long getLength()
```


Mendapatkan atau mengatur panjang stream dalam byte. Nilai ini lebih kecil daripada  System.IO.Stream.Length  sebesar posisi awal stream yang diberikan dalam konstruktor StreamContainer.

Nilai: Panjang stream.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Mendapatkan atau mengatur posisi saat ini dalam stream. Nilai ini mewakili offset dari posisi awal stream yang diberikan dalam konstruktor StreamContainer.

Nilai: Posisi stream saat ini.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Menampilkan aliran data.

Nilai: Stream data.

**Returns:**
java.io.InputStream
### getStream_internalized() {#getStream-internalized--}
```
public System.IO.Stream getStream_internalized()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
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
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.psd.StreamContainer-boolean-}
```
public final void insert(int position, StreamContainer stream, boolean disposeStream)
```


Menyisipkan kontainer aliran ke posisi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | int | Posisi untuk menyisipkan. |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer stream untuk disisipkan. |
| disposeStream | boolean | jika diatur ke  true  menutup stream. |

### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Menampilkan nilai yang menunjukkan apakah aliran ini dibuang saat ditutup.

Nilai:  true  jika stream dibuang saat ditutup; jika tidak,  false .

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




### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Membaca byte untuk mengisi buffer byte yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| byte | byte[] | Byte untuk mengisi. |

**Returns:**
int - Jumlah byte yang dibaca. Nilai ini dapat lebih kecil daripada jumlah byte dalam buffer jika tidak cukup byte dalam stream.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebanyak jumlah byte yang dibaca.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | byte[] | Array byte. Ketika metode ini mengembalikan, buffer berisi array byte yang ditentukan dengan nilai antara  offset  dan ( offset  +  count  - 1) digantikan oleh byte yang dibaca dari sumber saat ini. |
| offset | int | Offset byte berbasis nol dalam  buffer  dimana mulai menyimpan data yang dibaca dari stream saat ini. |
| count | int | Jumlah maksimum byte yang akan dibaca dari stream saat ini. |

**Returns:**
int - Total jumlah byte yang dibaca ke dalam buffer. Ini dapat lebih kecil daripada jumlah byte yang diminta jika byte tersebut tidak tersedia saat ini, atau nol (0) jika akhir stream telah tercapai.
### readByte() {#readByte--}
```
public int readByte()
```


Membaca satu byte dari aliran dan memajukan posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran.

**Returns:**
int - Byte tak bertanda yang dikonversi ke Int32, atau -1 jika berada di akhir stream.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Menyimpan (menyalin) data stream ke stream yang ditentukan. Menggunakan ukuran buffer default  ReadWriteBytesCount  dan nilai stream  Length .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Stream untuk menyimpan data. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Menyimpan (menyalin) semua data stream ke stream yang ditentukan. Menggunakan nilai stream  Length .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Stream untuk menyimpan data. |
| bufferSize | int | Buffer. |

### save(OutputStream dstStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream dstStream, int bufferSize, long length)
```


Menyimpan (menyalin) data aliran ke aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dstStream | java.io.OutputStream | Stream untuk menyimpan data. |
| bufferSize | int | Ukuran buffer. Secara default nilai [StreamContainer.READ\_WRITE\_BYTES\_COUNT](../../com.aspose.psd/streamcontainer\#READ-WRITE-BYTES-COUNT) digunakan. |
| length | long | Panjang data aliran yang akan disalin. Secara default panjang diatur ke nilai Length ([StreamContainer.getLength()](../../com.aspose.psd/streamcontainer\#getLength--)/[StreamContainer.setLength(long)](../../com.aspose.psd/streamcontainer\#setLength-long-)). |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Menyimpan (menyalin) data stream ke stream yang ditentukan. Menggunakan ukuran buffer default  ReadWriteBytesCount  dan nilai stream  Length .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Path file untuk menyimpan data aliran. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan nilai Length aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Path file untuk menyimpan data aliran. |
| bufferSize | int | Ukuran buffer. Secara default nilai ReadWriteBytesCount digunakan. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Menyimpan (menyalin) data aliran ke aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Path file untuk menyimpan data aliran. |
| bufferSize | int | Ukuran buffer. Secara default nilai ReadWriteBytesCount digunakan. |
| panjang | long | Panjang data aliran yang akan disalin. Secara default panjang diatur ke nilai Length. |

### save_internalized(System.IO.Stream destinationStream, int bufferSize, long length) {#save-internalized-com.aspose.ms.System.IO.Stream-int-long-}
```
public void save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destinationStream | com.aspose.ms.System.IO.Stream |  |
| bufferSize | int |  |
| panjang | long |  |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Mengatur posisi dalam aliran saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| offset | long | Offset byte relatif terhadap parameter origin. Nilai ini mewakili offset dari posisi awal aliran yang diberikan pada konstruktor StreamContainer. |
| origin | int | Nilai bertipe [SeekOrigin](../../com.aspose.psd/seekorigin) yang menunjukkan titik referensi yang digunakan untuk memperoleh posisi baru. |

**Returns:**
long - Posisi baru dalam aliran saat ini.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Mengatur posisi aliran ke awal aliran. Nilai ini mewakili offset dari posisi awal aliran yang diberikan pada konstruktor StreamContainer.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Mendapatkan atau mengatur panjang stream dalam byte. Nilai ini lebih kecil daripada  System.IO.Stream.Length  sebesar posisi awal stream yang diberikan dalam konstruktor StreamContainer.

Nilai: Panjang stream.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Mendapatkan atau mengatur posisi saat ini dalam stream. Nilai ini mewakili offset dari posisi awal stream yang diberikan dalam konstruktor StreamContainer.

Nilai: Posisi stream saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Mengonversi data aliran menjadi array  byte .

**Returns:**
byte[] - Data aliran yang dikonversi ke array byte.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Mengonversi data aliran menjadi array  byte .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | long | Posisi untuk memulai membaca byte. |
| bytesCount | long | Jumlah byte yang akan dibaca. |

**Returns:**
byte[] - Data aliran yang dikonversi ke array byte.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Melakukan konversi eksplisit dari  com.aspose.imaging.StreamContainer  ke  System.IO.Stream .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran. |

**Returns:**
com.aspose.ms.System.IO.Stream - Hasil konversi.
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Menulis semua byte yang ditentukan ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| byte | byte[] | Byte yang akan ditulis. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini sebanyak jumlah byte yang ditulis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | byte[] | Array byte. Metode ini menyalin count byte dari buffer ke aliran saat ini. |
| offset | int | Offset byte berbasis nol dalam buffer tempat memulai menyalin byte ke aliran saat ini. |
| count | int | Jumlah byte yang akan ditulis ke aliran saat ini. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran satu byte.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte | Byte yang akan ditulis ke aliran. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Mengopi data yang terkandung ke StreamContainer lain .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran untuk disalin ke. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Mengopi data yang terkandung ke StreamContainer lain .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran untuk disalin ke. |
| panjang | long | Jumlah byte yang akan ditulis. |

