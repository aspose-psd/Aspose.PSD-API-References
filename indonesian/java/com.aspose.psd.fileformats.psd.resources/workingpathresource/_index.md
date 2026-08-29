---
title: "WorkingPathResource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Sumber daya jalur kerja."
type: docs
weight: 43
url: /id/java/com.aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class WorkingPathResource extends ResourceBlock implements IVectorPathData
```

Sumber daya jalur kerja.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WorkingPathResource(byte[] dataBytes)](#WorkingPathResource-byte---) | Menginisialisasi sebuah instance baru dari kelas [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource). |
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
| [getDataSize()](#getDataSize--) | Mendapatkan ukuran data sumber daya dalam byte. |
| [getID()](#getID--) | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| [getMinimalVersion()](#getMinimalVersion--) | Mendapatkan versi PSD minimal yang diperlukan. |
| [getName()](#getName--) | Mendapatkan atau mengatur nama sumber daya. |
| [getPaths()](#getPaths--) | Mendapatkan atau mengatur catatan jalur. |
| [getSignature()](#getSignature--) | Mendapatkan tanda tangan sumber daya. |
| [getSize()](#getSize--) | Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya. |
| [getVersion()](#getVersion--) | Mendapatkan atau mengatur versi. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dinonaktifkan. |
| [isInverted()](#isInverted--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terbalik. |
| [isNotLinked()](#isNotLinked--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dinonaktifkan. |
| [setID(short value)](#setID-short-) | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| [setInverted(boolean value)](#setInverted-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terbalik. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Mendapatkan atau mengatur informasi layer dan mask. |
| [setName(String value)](#setName-java.lang.String-) | Mendapatkan atau mengatur nama sumber daya. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Mendapatkan atau mengatur catatan jalur. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Mendapatkan atau mengatur status blok sumber daya. |
| [setVersion(int value)](#setVersion-int-) | Mendapatkan atau mengatur versi. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Memvalidasi nilai sumber daya. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WorkingPathResource(byte[] dataBytes) {#WorkingPathResource-byte---}
```
public WorkingPathResource(byte[] dataBytes)
```


Menginisialisasi sebuah instance baru dari kelas [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataBytes | byte[] | Data jalur vektor. |

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
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Mendapatkan atau mengatur catatan jalur.

Nilai: Jalur.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
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
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Mendapatkan atau mengatur versi.

Nilai: Versi.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dinonaktifkan.

Nilai:  true  jika instance ini dinonaktifkan; jika tidak,  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terbalik.

Nilai:  true  jika instance ini terbalik; jika tidak,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung.

Nilai:  true  jika instance ini tidak terhubung; jika tidak,  false .

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Menyimpan blok sumber daya ke aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Aliran untuk menyimpan blok sumber daya. |

### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dinonaktifkan.

Nilai:  true  jika instance ini dinonaktifkan; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terbalik.

Nilai:  true  jika instance ini terbalik; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung.

Nilai:  true  jika instance ini tidak terhubung; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Mendapatkan atau mengatur catatan jalur.

Nilai: Jalur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

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

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Mendapatkan atau mengatur versi.

Nilai: Versi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

