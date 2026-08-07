---
title: "FileStreamContainer"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pembantu untuk pemrosesan aliran file."
type: docs
weight: 44
url: /id/java/com.aspose.psd/filestreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Pembantu untuk pemrosesan aliran file.
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
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Membuat aliran file baru. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Menghapus semua buffer untuk aliran ini dan menyebabkan data yang di-buffer ditulis ke perangkat dasar. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getFilePath()](#getFilePath--) | Mendapatkan jalur file. |
| [getLength()](#getLength--) | Menampilkan atau mengatur panjang aliran dalam byte. |
| [getPosition()](#getPosition--) | Menampilkan atau mengatur posisi saat ini dalam aliran. |
| [getStream()](#getStream--) | Menampilkan aliran data. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan. |
| [hashCode()](#hashCode--) |  |
| [isCreated()](#isCreated--) | Mendapatkan nilai yang menunjukkan apakah aliran dibuat secara eksplisit. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Menampilkan nilai yang menunjukkan apakah aliran ini dibuang saat ditutup. |
| [isTemporal()](#isTemporal--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah aliran bersifat temporal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Membuka aliran file yang ada. |
| [openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)](#openFileStream-internalized-java.lang.String-boolean-) | Membuka aliran file yang ada. |
| [read(byte[] bytes)](#read-byte---) | Membaca byte untuk mengisi buffer byte yang ditentukan. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebanyak jumlah byte yang dibaca. |
| [readByte()](#readByte--) | Membaca satu byte dari aliran dan memajukan posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Menyimpan (menyalin) semua data aliran ke aliran yang ditentukan. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [save(String filePath)](#save-java.lang.String-) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [seek(long offset, int origin)](#seek-long-int-) | Mengatur posisi dalam aliran saat ini. |
| [seekBegin()](#seekBegin--) | Mengatur posisi aliran ke awal aliran. |
| [setLength(long value)](#setLength-long-) | Menampilkan atau mengatur panjang aliran dalam byte. |
| [setPosition(long value)](#setPosition-long-) | Menampilkan atau mengatur posisi saat ini dalam aliran. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah aliran bersifat temporal. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Mengonversi data aliran menjadi array  byte . |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Mengonversi data aliran menjadi array  byte . |
| [toString()](#toString--) |  |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.psd.FileStreamContainer-) | Melakukan konversi eksplisit dari [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) ke FileInputStream. |
| [to_FileStream_internalized(FileStreamContainer fileStreamContainer)](#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.psd.FileStreamContainer-) | Melakukan konversi eksplisit dari [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) ke java.io.InputStream. |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Melakukan konversi eksplisit dari  com.aspose.imaging.StreamContainer  ke  System.IO.Stream . |
| [to_Stream_internalized(FileStreamContainer fileStreamContainer)](#to-Stream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Menulis semua byte yang ditentukan ke aliran. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini sebanyak jumlah byte yang ditulis. |
| [writeByte(byte value)](#writeByte-byte-) | Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran satu byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Mengopi data yang terkandung ke StreamContainer lain . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Mengopi data yang terkandung ke StreamContainer lain . |
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

### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Membuat aliran file baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileLocation | java.lang.String | Lokasi file. |
| isTemporal | boolean | Jika diatur ke  true  kontainer aliran file bersifat temporal. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
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
### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


Mendapatkan jalur file.

Nilai: Jalur file.

**Returns:**
java.lang.String
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
### isCreated() {#isCreated--}
```
public final boolean isCreated()
```


Mendapatkan nilai yang menunjukkan apakah aliran dibuat secara eksplisit.

Nilai:  true  jika aliran dibuat secara eksplisit; jika tidak,  false .

**Returns:**
boolean
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Menampilkan nilai yang menunjukkan apakah aliran ini dibuang saat ditutup.

Nilai:  true  jika stream dibuang saat ditutup; jika tidak,  false .

**Returns:**
boolean
### isTemporal() {#isTemporal--}
```
public final boolean isTemporal()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah aliran bersifat temporal.

Nilai:  true  jika aliran bersifat temporal; jika tidak,  false .

--------------------

Aliran temporal akan menghapus dirinya sendiri saat dibuang. Jika aliran berbasis memori, properti ini tidak berpengaruh. Aliran dapat ditandai sebagai temporal atau persisten jika dibuat secara eksplisit; jika tidak, pengecualian yang sesuai akan dilempar.

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




### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Membuka aliran file yang ada. Jika aliran file tidak ada, pengecualian yang sesuai akan dilempar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileLocation | java.lang.String | Lokasi file. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams) {#openFileStream-internalized-java.lang.String-boolean-}
```
public static FileStreamContainer openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)
```


Membuka aliran file yang ada. Jika aliran file tidak ada, pengecualian yang sesuai akan dilempar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileLocation | java.lang.String | Lokasi file. |
| disposeDuplicatedStreams | boolean | Jika diatur ke  true  akan membuang aliran duplikat. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
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

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Menyimpan (menyalin) data aliran ke aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Stream untuk menyimpan data. |
| bufferSize | int | Ukuran buffer. Secara default nilai ReadWriteBytesCount digunakan. |
| panjang | long | Panjang data aliran yang akan disalin. Secara default panjang diatur ke nilai Length. |

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

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Mengatur posisi dalam aliran saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| offset | long | Offset byte relatif terhadap parameter origin. Nilai ini mewakili offset dari posisi awal aliran yang diberikan pada konstruktor StreamContainer. |
| origin | int | Nilai bertipe  System.IO.SeekOrigin  yang menunjukkan titik referensi yang digunakan untuk memperoleh posisi baru. |

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

### setTemporal(boolean value) {#setTemporal-boolean-}
```
public final void setTemporal(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah aliran bersifat temporal.

Nilai:  true  jika aliran bersifat temporal; jika tidak,  false .

--------------------

Aliran temporal akan menghapus dirinya sendiri saat dibuang. Jika aliran berbasis memori, properti ini tidak berpengaruh. Aliran dapat ditandai sebagai temporal atau persisten jika dibuat secara eksplisit; jika tidak, pengecualian yang sesuai akan dilempar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.psd.FileStreamContainer-}
```
public static FileInputStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Melakukan konversi eksplisit dari [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) ke FileInputStream.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | Kontainer aliran file. |

**Returns:**
java.io.FileInputStream - Hasil konversi.
### to_FileStream_internalized(FileStreamContainer fileStreamContainer) {#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.FileStream
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.psd.FileStreamContainer-}
```
public static InputStream to_Stream(FileStreamContainer fileStreamContainer)
```


Melakukan konversi eksplisit dari [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) ke java.io.InputStream.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | Kontainer aliran file. |

**Returns:**
java.io.InputStream - Hasil konversi.
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
### to_Stream_internalized(FileStreamContainer fileStreamContainer) {#to-Stream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.Stream to_Stream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.Stream
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

