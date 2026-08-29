---
title: "UrlListResource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Sumber daya daftar URL"
type: docs
weight: 40
url: /id/java/com.aspose.psd.fileformats.psd.resources/urllistresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class UrlListResource extends ResourceBlock
```

Sumber daya daftar URL
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [UrlListResource()](#UrlListResource--) | Menginisialisasi instance baru dari kelas [UrlListResource](../../com.aspose.psd.fileformats.psd.resources/urllistresource). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Tanda tangan sumber daya ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Tanda tangan sumber daya Photoshop standar. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Mendapatkan atau mengatur jumlah. |
| [getDataSize()](#getDataSize--) | Mendapatkan ukuran data sumber daya dalam byte. |
| [getID()](#getID--) | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| [getIds()](#getIds--) | Mendapatkan atau mengatur id. |
| [getLongs()](#getLongs--) | Mendapatkan atau mengatur nilai long. |
| [getMinimalVersion()](#getMinimalVersion--) | Mendapatkan versi PSD minimal yang diperlukan. |
| [getName()](#getName--) | Mendapatkan atau mengatur nama sumber daya. |
| [getSignature()](#getSignature--) | Mendapatkan tanda tangan sumber daya. |
| [getSize()](#getSize--) | Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya. |
| [getTexts()](#getTexts--) | Mendapatkan atau mengatur teks. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| [setCount(int value)](#setCount-int-) | Mendapatkan atau mengatur jumlah. |
| [setID(short value)](#setID-short-) | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| [setIds(int[] value)](#setIds-int---) | Mendapatkan atau mengatur id. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Mendapatkan atau mengatur informasi layer dan mask. |
| [setLongs(int[] value)](#setLongs-int---) | Mendapatkan atau mengatur nilai long. |
| [setName(String value)](#setName-java.lang.String-) | Mendapatkan atau mengatur nama sumber daya. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Mendapatkan atau mengatur status blok sumber daya. |
| [setTexts(String[] value)](#setTexts-java.lang.String---) | Mendapatkan atau mengatur teks. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Memvalidasi nilai sumber daya. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### UrlListResource() {#UrlListResource--}
```
public UrlListResource()
```


Menginisialisasi instance baru dari kelas [UrlListResource](../../com.aspose.psd.fileformats.psd.resources/urllistresource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Tanda tangan sumber daya ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Tanda tangan sumber daya Photoshop standar.

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
### getCount() {#getCount--}
```
public final int getCount()
```


Mendapatkan atau mengatur jumlah.

Nilai: Jumlah.

**Returns:**
int
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Mendapatkan ukuran data sumber daya dalam byte.

Nilai: Ukuran data sumber daya.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya.

Nilai: Pengidentifikasi unik untuk sumber daya.

**Returns:**
short
### getIds() {#getIds--}
```
public final int[] getIds()
```


Mendapatkan atau mengatur id.

Nilai: Id.

**Returns:**
int[]
### getLongs() {#getLongs--}
```
public final int[] getLongs()
```


Mendapatkan atau mengatur nilai long.

Nilai: Nilai long.

**Returns:**
int[]
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Mendapatkan versi PSD minimal yang diperlukan.

Nilai: Versi PSD minimal.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0).

Nilai: Nama sumber daya.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Mendapatkan tanda tangan sumber daya. Harus selalu '8BIM'.

Nilai: Tanda tangan sumber daya.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya.

Nilai: Ukuran blok sumber daya.

**Returns:**
int
### getTexts() {#getTexts--}
```
public final String[] getTexts()
```


Mendapatkan atau mengatur teks.

Nilai: Teks.

**Returns:**
java.lang.String[]
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Menyimpan blok sumber daya ke aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Aliran untuk menyimpan blok sumber daya. |

### setCount(int value) {#setCount-int-}
```
public final void setCount(int value)
```


Mendapatkan atau mengatur jumlah.

Nilai: Jumlah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya.

Nilai: Pengidentifikasi unik untuk sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setIds(int[] value) {#setIds-int---}
```
public final void setIds(int[] value)
```


Mendapatkan atau mengatur id.

Nilai: Id.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Mendapatkan atau mengatur informasi layer dan mask.

Nilai: Informasi lapisan dan masker.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setLongs(int[] value) {#setLongs-int---}
```
public final void setLongs(int[] value)
```


Mendapatkan atau mengatur nilai long.

Nilai: Nilai long.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0).

Nilai: Nama sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tanda tangan | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Mendapatkan atau mengatur status blok sumber daya.

Nilai: Status blok sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTexts(String[] value) {#setTexts-java.lang.String---}
```
public final void setTexts(String[] value)
```


Mendapatkan atau mengatur teks.

Nilai: Teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Memvalidasi nilai sumber daya.

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

