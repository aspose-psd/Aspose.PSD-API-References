---
title: "VectorPathData"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas untuk bekerja dengan jalur vektor."
type: docs
weight: 18
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

Kelas untuk bekerja dengan jalur vektor.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | Menginisialisasi instance baru dari kelas [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
| [VectorPathData()](#VectorPathData--) | Menginisialisasi instance baru dari kelas [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | Ukuran informasi umum seperti versi dan flag. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | Mendapatkan sebagai array byte. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Mendapatkan panjang data jalur vektor dalam sumber daya sebagai byte. |
| [getPaths()](#getPaths--) | Mendapatkan atau mengatur catatan jalur. |
| [getVersion()](#getVersion--) | Mendapatkan atau mengatur versi. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dinonaktifkan. |
| [isInverted()](#isInverted--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terbalik. |
| [isNotLinked()](#isNotLinked--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dinonaktifkan. |
| [setInverted(boolean value)](#setInverted-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terbalik. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Mendapatkan atau mengatur catatan jalur. |
| [setVersion(int value)](#setVersion-int-) | Mendapatkan atau mengatur versi. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


Menginisialisasi instance baru dari kelas [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data resource. |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


Menginisialisasi instance baru dari kelas [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


Ukuran informasi umum seperti versi dan flag.

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


Mendapatkan sebagai array byte.

**Returns:**
byte[] - Sumber daya sebagai array byte.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


Mendapatkan panjang data jalur vektor dalam sumber daya sebagai byte.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Mendapatkan atau mengatur catatan jalur.

Nilai: Jalur.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
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

