---
title: "Zaman Çizelgesi"
second_title: "Java için Aspose.PSD API Referansı"
description: "Zaman çizelgesi seçenekleri modeli."
type: docs
weight: 14
url: /tr/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

Zaman çizelgesi seçenekleri modeli.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Timeline()](#Timeline--) | Yeni bir [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | Geçerli zaman çizelgesi değerlerini giriş PsdImage'e uygula ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | AFSt değerini alır veya ayarlar. |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | Aktif çerçeve indeksini alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | Kimliğe göre çerçeveyi alır. |
| [getFrames()](#getFrames--) | Çerçevelerin listesini alır. |
| [getFramesList()](#getFramesList--) | Çerçevelerin listesini alır. |
| [getFsID()](#getFsID--) | FsID değerini alır veya ayarlar. |
| [getLoopesCount()](#getLoopesCount--) | Döngü sayısını alır veya ayarlar. |
| [getPsdImage()](#getPsdImage--) | Bu [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) nesnesinin PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) değerini alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen biçimde belirtilen akışa kaydeder. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen biçimde belirtilen dosya konumuna kaydeder. |
| [setAFSt(int value)](#setAFSt-int-) | AFSt değerini alır veya ayarlar. |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | Aktif çerçeve indeksini alır veya ayarlar. |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | Çerçevelerin listesini alır. |
| [setFsID(int value)](#setFsID-int-) | FsID değerini alır veya ayarlar. |
| [setLoopesCount(int value)](#setLoopesCount-int-) | Döngü sayısını alır veya ayarlar. |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | Bu [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) nesnesinin PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) değerini alır veya ayarlar. |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | Aktif çerçeveyi hedeflenen çerçeveye değiştirir. |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | Geçerli zaman çizelgesi değerlerini giriş PsdImage'e uygula ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


Yeni bir [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) sınıfının örneğini başlatır.

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


Geçerli zaman çizelgesi değerlerini giriş PsdImage'e uygula ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | psd görüntüsü. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


AFSt değerini alır veya ayarlar.

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


Aktif çerçeve indeksini alır veya ayarlar.

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


Kimliğe göre çerçeveyi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frameId | int | Çerçeve kimliği. |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


Çerçevelerin listesini alır.

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


Çerçevelerin listesini alır.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


FsID değerini alır veya ayarlar.

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


Döngü sayısını alır veya ayarlar.

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


Bu [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) nesnesinin PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) değerini alır veya ayarlar.

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


PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen biçimde belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | Çıktı akışı. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Seçenekler. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen biçimde belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Seçenekler. |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


AFSt değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


Aktif çerçeve indeksini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


Çerçevelerin listesini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


FsID değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


Döngü sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


Bu [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) nesnesinin PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


Aktif çerçeveyi hedeflenen çerçeveye değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetActiveFrameIndex | int | Hedef çerçeve indeksi. |

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


Geçerli zaman çizelgesi değerlerini giriş PsdImage'e uygula ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frameIndex | int | Katman durumlarını güncellemek için çerçeve indeksi. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

