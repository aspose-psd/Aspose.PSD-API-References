---
title: "PattResourceData"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas untuk menyimpan data pola untuk sumber daya."
type: docs
weight: 67
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

Kelas untuk menyimpan data pola untuk sumber daya [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | Menginisialisasi sebuah instance baru dari kelas [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | Mengembalikan kode metode kompresi yang diperoleh dari saluran pattern\\u2019s. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | Membuat data pola default. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi. |
| [getImageMode()](#getImageMode--) | Mendapatkan mode gambar. |
| [getLength()](#getLength--) | Mendapatkan panjang pola. |
| [getName()](#getName--) | Mendapatkan atau mengatur nama. |
| [getPatternData()](#getPatternData--) | Mendapatkan data pola. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | Daftar array memori. |
| [getPatternId()](#getPatternId--) | Mendapatkan atau mengatur pengidentifikasi pola. |
| [getVersion()](#getVersion--) | Mendapatkan versi. |
| [getWidth()](#getWidth--) | Mendapatkan lebar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Menyimpan data pola. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | Mendapatkan tinggi. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | Mendapatkan mode gambar. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | Mendapatkan atau mengatur tabel warna indeks. |
| [setName(String value)](#setName-java.lang.String-) | Mendapatkan atau mengatur nama. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | Mengatur buffer piksel pola dan ukuran target, memperbarui  Lebar ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Tinggi ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), dan menyimpan data untuk penyimpanan menggunakan mode kompresi default (0). |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | Daftar array memori. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Mendapatkan atau mengatur pengidentifikasi pola. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | Mengatur buffer piksel pola dan ukuran target, memperbarui  Lebar ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Tinggi ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), dan menyimpan data untuk penyimpanan menggunakan mode kompresi yang ditentukan. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Mendapatkan versi. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | Mendapatkan lebar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


Menginisialisasi sebuah instance baru dari kelas [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

### createNewInstance_internalized() {#createNewInstance-internalized--}
```
public static PattResourceData createNewInstance_internalized()
```




**Returns:**
[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)
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
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


Mengembalikan kode metode kompresi yang diperoleh dari saluran pattern\\u2019s.

**Returns:**
byte - Kode kompresi: 0 \\u2014 mentah/tidak terkompresi; >= 1 \\u2014 zip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPattern_internalized() {#getDefaultPattern-internalized--}
```
public static PixelsData getDefaultPattern_internalized()
```


Membuat data pola default.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


Mendapatkan tinggi.

Nilai: Tinggi.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


Mendapatkan mode gambar.

Nilai: Mode gambar.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


Mendapatkan panjang pola.

Nilai: Panjang pola.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Mendapatkan atau mengatur nama.

Nilai: Nama.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Mendapatkan data pola.

Nilai: Data pola.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


Daftar array memori.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Mendapatkan atau mengatur pengidentifikasi pola.

Nilai: Pengidentifikasi pola.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Mendapatkan versi.

Nilai: Versi.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


Mendapatkan lebar.

Nilai: Lebar.

**Returns:**
short
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




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Menyimpan data pola.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


Mendapatkan tinggi.

Nilai: Tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


Mendapatkan mode gambar.

Nilai: Mode gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


Mendapatkan atau mengatur tabel warna indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Mendapatkan atau mengatur nama.

Nilai: Nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


Mengatur buffer piksel pola dan ukuran target, memperbarui  Lebar ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Tinggi ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), dan menyimpan data untuk penyimpanan menggunakan mode kompresi default (0).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| piksel | int[] | Piksel 32-bit dalam format 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas piksel pola. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


Daftar array memori.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Mendapatkan atau mengatur pengidentifikasi pola.

Nilai: Pengidentifikasi pola.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


Mengatur buffer piksel pola dan ukuran target, memperbarui  Lebar ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Tinggi ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), dan menyimpan data untuk penyimpanan menggunakan mode kompresi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| piksel | int[] | Piksel 32-bit dalam format 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas piksel pola. |
| compressionMode | byte | Mode kompresi yang digunakan untuk menentukan kompresi data pola saat menyimpan file psd. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Mendapatkan versi.

Nilai: Versi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


Mendapatkan lebar.

Nilai: Lebar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

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

