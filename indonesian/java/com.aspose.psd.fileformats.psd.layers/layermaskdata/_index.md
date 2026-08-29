---
title: "LayerMaskData"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan kelas dasar LayerMaskData yang berisi informasi tentang data topeng lapisan dalam file PSD."
type: docs
weight: 21
url: /id/java/com.aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public abstract class LayerMaskData implements Cloneable
```

Mendefinisikan kelas dasar LayerMaskData yang berisi informasi tentang data mask lapisan dalam file PSD. Ini dapat membantu memodifikasi file Adobe\\ufffd Photoshop\\ufffd secara programatik dan mengotomatiskan penyuntingan format PSD. Jika lapisan hanya memiliki mask raster, ImageData berisi byte data mask raster. Jika lapisan hanya memiliki mask vektor, ImageData berisi byte data mask vektor yang dirasterkan (di‑cache). Jika lapisan memiliki mask raster dan vektor, ImageData berisi kombinasi mask raster dan mask vektor yang dirasterkan. Panjang byte ImageData ([getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) harus sama dengan Lebar \* Tinggi dari properti MaskRectangle ([getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)). Perhatikan bahwa hanya menghapus / menambahkan / memperbarui LayerMaskData tidak cukup untuk penyimpanan yang benar karena saluran tidak diperbarui; meskipun dapat memberikan rendering yang tepat. Metode [Layer.addLayerMask(LayerMaskData)](../../com.aspose.psd.fileformats.psd.layers/layer\#addLayerMask-LayerMaskData-) harus digunakan untuk itu.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Mengkloning instance ini. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Mengkloning mask lapisan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Mendapatkan atau mengatur posisi mask lapisan bagian bawah. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Mendapatkan ukuran data mask lapisan. |
| [getDefaultColor()](#getDefaultColor--) | Mendapatkan atau mengatur warna default. |
| [getFlags()](#getFlags--) | Mendapatkan atau mengatur flag mask lapisan. |
| [getHeight_internalized()](#getHeight-internalized--) | Mendapatkan tinggi mask. |
| [getImageData()](#getImageData--) | Mendapatkan atau mengatur data mask lapisan (atau mask gabungan / akhir jika ada mask vektor) dalam file PSD. |
| [getLeft()](#getLeft--) | Mendapatkan atau mengatur posisi mask lapisan kiri. |
| [getMaskRectangle()](#getMaskRectangle--) | Mendapatkan atau mengatur Rectangle mask lapisan dalam file PSD. |
| [getRight()](#getRight--) | Mendapatkan atau mengatur posisi mask lapisan kanan. |
| [getTop()](#getTop--) | Mendapatkan atau mengatur posisi mask lapisan atas. |
| [getWidth_internalized()](#getWidth-internalized--) | Mendapatkan lebar mask. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Menyimpan [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) ke StreamContainer yang ditentukan. |
| [setBottom(int value)](#setBottom-int-) | Mendapatkan atau mengatur posisi mask lapisan bagian bawah. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Mendapatkan atau mengatur warna default. |
| [setFlags(byte value)](#setFlags-byte-) | Mendapatkan atau mengatur flag mask lapisan. |
| [setImageData(byte[] value)](#setImageData-byte---) | Mendapatkan atau mengatur data mask lapisan (atau mask gabungan / akhir jika ada mask vektor) dalam file PSD. |
| [setLeft(int value)](#setLeft-int-) | Mendapatkan atau mengatur posisi mask lapisan kiri. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Mendapatkan atau mengatur Rectangle mask lapisan dalam file PSD. |
| [setRight(int value)](#setRight-int-) | Mendapatkan atau mengatur posisi mask lapisan kanan. |
| [setTop(int value)](#setTop-int-) | Mendapatkan atau mengatur posisi mask lapisan atas. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Mengkloning instance ini.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Mengkloning mask lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Mask. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Mendapatkan atau mengatur posisi mask lapisan bagian bawah.

Nilai: Posisi mask lapisan bagian bawah.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


Mendapatkan ukuran data mask lapisan.

Nilai: Ukuran data masker lapisan.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Mendapatkan atau mengatur warna default.

Nilai: Warna default.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Mendapatkan atau mengatur flag mask lapisan.

Nilai: Bendera masker lapisan.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Mendapatkan tinggi mask.

Nilai: Tinggi.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Mendapatkan atau mengatur data mask lapisan (atau mask gabungan / akhir jika ada mask vektor) dalam file PSD.

Nilai: Data gambar.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Mendapatkan atau mengatur posisi mask lapisan kiri.

Nilai: Posisi kiri masker lapisan.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Mendapatkan atau mengatur Rectangle masker lapisan dalam file PSD. Ini mengambil properti kiri, kanan, atas, dan bawah serta membuat Rectangle

Nilai: Rectangle masker.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getRight() {#getRight--}
```
public final int getRight()
```


Mendapatkan atau mengatur posisi mask lapisan kanan.

Nilai: Posisi kanan masker lapisan.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Mendapatkan atau mengatur posisi mask lapisan atas.

Nilai: Posisi atas masker lapisan.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Mendapatkan lebar mask.

Nilai: Lebar.

**Returns:**
int
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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public abstract void save_internalized(StreamContainer streamContainer)
```


Menyimpan [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) ke StreamContainer yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran untuk menyimpan data. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Mendapatkan atau mengatur posisi mask lapisan bagian bawah.

Nilai: Posisi mask lapisan bagian bawah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Mendapatkan atau mengatur warna default.

Nilai: Warna default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Mendapatkan atau mengatur flag mask lapisan.

Nilai: Bendera masker lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


Mendapatkan atau mengatur data mask lapisan (atau mask gabungan / akhir jika ada mask vektor) dalam file PSD.

Nilai: Data gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Mendapatkan atau mengatur posisi mask lapisan kiri.

Nilai: Posisi kiri masker lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


Mendapatkan atau mengatur Rectangle masker lapisan dalam file PSD. Ini mengambil properti kiri, kanan, atas, dan bawah serta membuat Rectangle

Nilai: Rectangle masker.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Mendapatkan atau mengatur posisi mask lapisan kanan.

Nilai: Posisi kanan masker lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Mendapatkan atau mengatur posisi mask lapisan atas.

Nilai: Posisi atas masker lapisan.

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

