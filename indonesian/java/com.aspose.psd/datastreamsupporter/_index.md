---
title: "DataStreamSupporter"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kontainer aliran data."
type: docs
weight: 38
url: /id/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Kontainer aliran data.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Terjadi ketika gambar dimuat atau disimpan |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Terjadi ketika kredit digunakan |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [cacheData()](#cacheData--) | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari DataStreamSupporter.DataStreamContainer yang mendasarinya. |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Mendapatkan aliran data objek. |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Mendapatkan jalur file gambar sumber jika ada. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Mendapatkan nilai yang menunjukkan apakah objek menggunakan strategi optimasi memori |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Mengambil nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Menyimpan data objek ke DataStreamSupporter saat ini. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Menyimpan data objek ke aliran yang ditentukan. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Menyimpan data objek ke aliran yang ditentukan. |
| [save(String filePath)](#save-java.lang.String-) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Menetapkan aliran data objek. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Menetapkan nilai yang menunjukkan apakah [ignore after save]. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Terjadi ketika gambar dimuat atau disimpan

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Terjadi ketika kredit digunakan

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari DataStreamSupporter.DataStreamContainer yang mendasarinya.

### close() {#close--}
```
public void close()
```


Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. Metode ini hanya memanggil metode dispose.

### dispose() {#dispose--}
```
public final void dispose()
```


Membuang instance saat ini.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Mendapatkan aliran data objek.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang.

**Returns:**
boolean - true jika dibuang; jika tidak, false.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Mendapatkan jalur file gambar sumber jika ada. Mengembalikan string kosong jika tidak dapat menemukan jalur sumber.

**Returns:**
java.lang.String - Jalur file gambar sumber.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Mendapatkan nilai yang menunjukkan apakah objek menggunakan strategi optimasi memori

Nilai:  true  jika objek menggunakan strategi optimasi memori; jika tidak,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah objek menggunakan strategi optimasi memori
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Mengambil nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data.

**Returns:**
boolean - nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


Menyimpan data objek ke DataStreamSupporter saat ini.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Menyimpan data objek ke aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran untuk menyimpan data objek. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Menyimpan data objek ke aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Aliran untuk menyimpan data objek. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Path file untuk menyimpan data objek. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Path file untuk menyimpan data objek. |
| overWrite | boolean | Jika diatur ke true, akan menimpa isi file; jika tidak, akan menambahkan. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Menetapkan aliran data objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Aliran data objek. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Menetapkan nilai yang menunjukkan apakah [ignore after save].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika [ignore after save]; jika tidak,  false . |

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

