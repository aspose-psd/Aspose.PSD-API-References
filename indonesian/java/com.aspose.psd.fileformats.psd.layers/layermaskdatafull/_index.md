---
title: "LayerMaskDataFull"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan kelas LayerMaskDataFull yang berisi informasi tentang data masker dalam lapisan file PSD ketika lapisan memiliki masker lapisan dan vektor."
type: docs
weight: 22
url: /id/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

Mendefinisikan kelas LayerMaskDataFull yang berisi informasi tentang data masker pada lapisan file PSD ketika lapisan memiliki masker lapisan dan vektor. Jika tidak, sebuah [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) digunakan. ImageData berisi masker raster dan masker vektor yang dirasterkan secara gabungan. Panjang byte ImageData harus sama dengan properti MaskRectangle.Width \* MaskRectangle.Height.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Menginisialisasi sebuah instance baru dari kelas [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Mengkloning instance ini. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Mengkloning mask lapisan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan atau mengatur warna latar belakang. |
| [getBottom()](#getBottom--) | Mendapatkan atau mengatur posisi mask lapisan bagian bawah. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Mendapatkan ukuran data mask lapisan. |
| [getDefaultColor()](#getDefaultColor--) | Mendapatkan atau mengatur warna default. |
| [getEnclosingBottom()](#getEnclosingBottom--) | Mendapatkan atau mengatur posisi raster mask bawah yang melingkupi dalam lapisan gambar PSD. |
| [getEnclosingLeft()](#getEnclosingLeft--) | Mendapatkan atau mengatur posisi raster mask kiri yang melingkupi dalam lapisan file PSD. |
| [getEnclosingRight()](#getEnclosingRight--) | Mendapatkan atau mengatur posisi raster mask kanan yang melingkupi dalam lapisan file PSD. |
| [getEnclosingTop()](#getEnclosingTop--) | Mendapatkan atau mengatur posisi atas raster mask yang melingkupi dalam lapisan gambar PSD. |
| [getFlags()](#getFlags--) | Mendapatkan atau mengatur flag mask lapisan. |
| [getHeight_internalized()](#getHeight-internalized--) | Mendapatkan tinggi mask. |
| [getImageData()](#getImageData--) | Mendapatkan atau mengatur data mask lapisan (atau mask gabungan / akhir jika ada mask vektor) dalam file PSD. |
| [getLeft()](#getLeft--) | Mendapatkan atau mengatur posisi mask lapisan kiri. |
| [getMaskRectangle()](#getMaskRectangle--) | Mendapatkan atau mengatur Rectangle mask lapisan dalam file PSD. |
| [getRealFlags()](#getRealFlags--) | Mendapatkan atau mengatur flag mask lapisan yang digunakan untuk mask pengguna / raster. |
| [getRight()](#getRight--) | Mendapatkan atau mengatur posisi mask lapisan kanan. |
| [getTop()](#getTop--) | Mendapatkan atau mengatur posisi mask lapisan atas. |
| [getUserMaskData()](#getUserMaskData--) | Mendapatkan atau mengatur data mask pengguna (raster) pada lapisan dalam file PSD. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | Mendapatkan atau mengatur persegi panjang mask pengguna (penutup) dalam lapisan gambar PSD. |
| [getWidth_internalized()](#getWidth-internalized--) | Mendapatkan lebar mask. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Menyimpan [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) ke StreamContainer yang ditentukan. |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Mendapatkan atau mengatur warna latar belakang. |
| [setBottom(int value)](#setBottom-int-) | Mendapatkan atau mengatur posisi mask lapisan bagian bawah. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Mendapatkan atau mengatur warna default. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | Mendapatkan atau mengatur posisi raster mask bawah yang melingkupi dalam lapisan gambar PSD. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | Mendapatkan atau mengatur posisi raster mask kiri yang melingkupi dalam lapisan file PSD. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | Mendapatkan atau mengatur posisi raster mask kanan yang melingkupi dalam lapisan file PSD. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | Mendapatkan atau mengatur posisi atas raster mask yang melingkupi dalam lapisan gambar PSD. |
| [setFlags(byte value)](#setFlags-byte-) | Mendapatkan atau mengatur flag mask lapisan. |
| [setImageData(byte[] value)](#setImageData-byte---) | Mendapatkan atau mengatur data mask lapisan (atau mask gabungan / akhir jika ada mask vektor) dalam file PSD. |
| [setLeft(int value)](#setLeft-int-) | Mendapatkan atau mengatur posisi mask lapisan kiri. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Mendapatkan atau mengatur Rectangle mask lapisan dalam file PSD. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Mendapatkan atau mengatur flag mask lapisan yang digunakan untuk mask pengguna / raster. |
| [setRight(int value)](#setRight-int-) | Mendapatkan atau mengatur posisi mask lapisan kanan. |
| [setTop(int value)](#setTop-int-) | Mendapatkan atau mengatur posisi mask lapisan atas. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | Mendapatkan atau mengatur data mask pengguna (raster) pada lapisan dalam file PSD. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | Mendapatkan atau mengatur persegi panjang mask pengguna (penutup) dalam lapisan gambar PSD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Menginisialisasi sebuah instance baru dari kelas [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull).

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Mendapatkan atau mengatur warna latar belakang.

Nilai: Warna latar belakang.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


Mendapatkan atau mengatur posisi raster mask bawah yang melingkupi dalam lapisan gambar PSD.

Nilai: Posisi mask lapisan bagian bawah.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


Mendapatkan atau mengatur posisi raster mask kiri yang melingkupi dalam lapisan file PSD.

Nilai: Posisi kiri masker lapisan.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


Mendapatkan atau mengatur posisi raster mask kanan yang melingkupi dalam lapisan file PSD.

Nilai: Posisi kanan masker lapisan.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


Mendapatkan atau mengatur posisi atas raster mask yang melingkupi dalam lapisan gambar PSD.

Nilai: Posisi atas masker lapisan.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Mendapatkan atau mengatur flag mask lapisan yang digunakan untuk mask pengguna / raster. Untuk mask vektor properti Flags digunakan.

Nilai: Flag mask lapisan yang sebenarnya.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


Mendapatkan atau mengatur data mask pengguna (raster) dari sebuah lapisan dalam file PSD. (Ada mask vektor yang dirasterkan dalam properti MaskData).

Nilai: Data gambar lapisan dalam gambar PSD.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


Mendapatkan atau mengatur persegi panjang mask pengguna (penutup) dalam lapisan gambar PSD.

Nilai: Persegi panjang mask pengguna.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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
public void save_internalized(StreamContainer streamContainer)
```


Menyimpan [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) ke StreamContainer yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran untuk menyimpan data. |

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Mendapatkan atau mengatur warna latar belakang.

Nilai: Warna latar belakang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


Mendapatkan atau mengatur posisi raster mask bawah yang melingkupi dalam lapisan gambar PSD.

Nilai: Posisi mask lapisan bagian bawah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


Mendapatkan atau mengatur posisi raster mask kiri yang melingkupi dalam lapisan file PSD.

Nilai: Posisi kiri masker lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


Mendapatkan atau mengatur posisi raster mask kanan yang melingkupi dalam lapisan file PSD.

Nilai: Posisi kanan masker lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


Mendapatkan atau mengatur posisi atas raster mask yang melingkupi dalam lapisan gambar PSD.

Nilai: Posisi atas masker lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Mendapatkan atau mengatur flag mask lapisan yang digunakan untuk mask pengguna / raster. Untuk mask vektor properti Flags digunakan.

Nilai: Flag mask lapisan yang sebenarnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


Mendapatkan atau mengatur data mask pengguna (raster) dari sebuah lapisan dalam file PSD. (Ada mask vektor yang dirasterkan dalam properti MaskData).

Nilai: Data gambar lapisan dalam gambar PSD.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


Mendapatkan atau mengatur persegi panjang mask pengguna (penutup) dalam lapisan gambar PSD.

Nilai: Persegi panjang mask pengguna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

