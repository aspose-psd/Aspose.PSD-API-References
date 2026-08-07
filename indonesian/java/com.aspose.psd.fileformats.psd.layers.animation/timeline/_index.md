---
title: "Timeline"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Model opsi garis waktu."
type: docs
weight: 14
url: /id/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

Model opsi garis waktu.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Timeline()](#Timeline--) | Menginisialisasi instance baru dari kelas [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | Terapkan nilai garis waktu saat ini ke PsdImage masukan ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | Mendapatkan atau mengatur nilai AFSt. |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | Mendapatkan atau mengatur indeks frame aktif. |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | Mendapatkan frame berdasarkan id. |
| [getFrames()](#getFrames--) | Mendapatkan daftar frame. |
| [getFramesList()](#getFramesList--) | Mendapatkan daftar frame. |
| [getFsID()](#getFsID--) | Mendapatkan atau mengatur nilai FsID. |
| [getLoopesCount()](#getLoopesCount--) | Mendapatkan atau mengatur jumlah loop. |
| [getPsdImage()](#getPsdImage--) | Mendapatkan atau mengatur PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) dari [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | Menyimpan data PsdImage dan Timeline ke aliran yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Menyimpan data PsdImage dan Timeline ke lokasi file yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan. |
| [setAFSt(int value)](#setAFSt-int-) | Mendapatkan atau mengatur nilai AFSt. |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | Mendapatkan atau mengatur indeks frame aktif. |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | Mendapatkan daftar frame. |
| [setFsID(int value)](#setFsID-int-) | Mendapatkan atau mengatur nilai FsID. |
| [setLoopesCount(int value)](#setLoopesCount-int-) | Mendapatkan atau mengatur jumlah loop. |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | Mendapatkan atau mengatur PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) dari [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | Mengalihkan frame aktif ke target. |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | Terapkan nilai garis waktu saat ini ke PsdImage masukan ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


Menginisialisasi instance baru dari kelas [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


Terapkan nilai garis waktu saat ini ke PsdImage masukan ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Gambar psd. |

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
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


Mendapatkan atau mengatur nilai AFSt.

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


Mendapatkan atau mengatur indeks frame aktif.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFrame(int frameId) {#getFrame-int-}
```
public Frame getFrame(int frameId)
```


Mendapatkan frame berdasarkan id.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| frameId | int | ID frame. |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


Mendapatkan daftar frame.

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


Mendapatkan daftar frame.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


Mendapatkan atau mengatur nilai FsID.

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


Mendapatkan atau mengatur jumlah loop.

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


Mendapatkan atau mengatur PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) dari [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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




### save(System.IO.Stream outputStream, ImageOptionsBase options) {#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-}
```
public void save(System.IO.Stream outputStream, ImageOptionsBase options)
```


Menyimpan data PsdImage dan Timeline ke aliran yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | Aliran keluaran. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Menyimpan data PsdImage dan Timeline ke lokasi file yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur berkas. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi. |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


Mendapatkan atau mengatur nilai AFSt.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


Mendapatkan atau mengatur indeks frame aktif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


Mendapatkan daftar frame.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


Mendapatkan atau mengatur nilai FsID.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


Mendapatkan atau mengatur jumlah loop.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


Mendapatkan atau mengatur PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) dari [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


Mengalihkan frame aktif ke target.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetActiveFrameIndex | int | Indeks frame target. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFrameFromPsdImage_internalized(int frameIndex) {#updateFrameFromPsdImage-internalized-int-}
```
public void updateFrameFromPsdImage_internalized(int frameIndex)
```


Terapkan nilai garis waktu saat ini ke PsdImage masukan ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| frameIndex | int | Indeks frame untuk memperbarui keadaan lapisan. |

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

