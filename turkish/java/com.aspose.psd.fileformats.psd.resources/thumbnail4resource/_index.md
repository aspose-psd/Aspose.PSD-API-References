---
title: "Thumbnail4Resource"
second_title: "Java için Aspose.PSD API Referansı"
description: "psd 4.0 için küçük resim kaynağını temsil eder."
type: docs
weight: 34
url: /tr/java/com.aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock), [com.aspose.psd.fileformats.psd.resources.ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource)
```
public final class Thumbnail4Resource extends ThumbnailResource
```

psd 4.0 için küçük resim kaynağını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Thumbnail4Resource()](#Thumbnail4Resource--) | Yeni bir [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource) sınıfının örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady'ın kaynak imzası. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Normal Photoshop kaynak imzası. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | Piksel başına bit sayısını alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Kaynak veri boyutunu bayt cinsinden alır. |
| [getFormat()](#getFormat--) | Küçük resim veri formatını alır veya ayarlar. |
| [getHeight()](#getHeight--) | Küçük resmin yüksekliğini piksel cinsinden alır veya ayarlar. |
| [getID()](#getID--) | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| [getJpegOptions()](#getJpegOptions--) | JPEG seçeneklerini alır veya ayarlar. |
| [getMinimalVersion()](#getMinimalVersion--) | Minimum gerekli psd sürümünü alır. |
| [getName()](#getName--) | Kaynak adını alır veya ayarlar. |
| [getPlanesCount()](#getPlanesCount--) | Düzlem sayısını alır veya ayarlar. |
| [getSignature()](#getSignature--) | Kaynak imzasını alır. |
| [getSize()](#getSize--) | Veri dahil olmak üzere kaynak blok boyutunu bayt cinsinden alır. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | Sıkıştırma sonrası boyutu alır veya ayarlar. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | 32-bit ARGB küçük resim verisini alır veya ayarlar. |
| [getThumbnailData()](#getThumbnailData--) | Küçük resim verisini alır veya ayarlar. |
| [getTotalSize()](#getTotalSize--) | Toplam veri boyutunu alır. |
| [getWidth()](#getWidth--) | Küçük resmin genişliğini piksel cinsinden alır veya ayarlar. |
| [getWidthBytes()](#getWidthBytes--) | Satır genişliğini bayt cinsinden alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Kaynak bloğunu belirtilen akışa kaydeder. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | Piksel başına bit sayısını alır veya ayarlar. |
| [setFormat(int value)](#setFormat-int-) | Küçük resim veri formatını alır veya ayarlar. |
| [setHeight(int value)](#setHeight-int-) | Küçük resmin yüksekliğini piksel cinsinden alır veya ayarlar. |
| [setID(short value)](#setID-short-) | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | JPEG seçeneklerini alır veya ayarlar. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Katman ve maske bilgilerini alır veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Kaynak adını alır veya ayarlar. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | Düzlem sayısını alır veya ayarlar. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Kaynak blok durumunu alır veya ayarlar. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | 32-bit ARGB küçük resim verisini alır veya ayarlar. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | Küçük resim verisini alır veya ayarlar. |
| [setWidth(int value)](#setWidth-int-) | Küçük resmin genişliğini piksel cinsinden alır veya ayarlar. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Kaynak değerlerini doğrular. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail4Resource() {#Thumbnail4Resource--}
```
public Thumbnail4Resource()
```


Yeni bir [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource) sınıfının örneğini başlatır.

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


ImageReady'ın kaynak imzası.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Normal Photoshop kaynak imzası.

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


Piksel başına bit sayısını alır veya ayarlar.

Değer: Küçük resim piksel başına bit sayısı.

**Returns:**
short
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


Kaynak veri boyutunu bayt cinsinden alır.

Değer: Kaynak veri boyutu.

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Küçük resim veri formatını alır veya ayarlar.

Değer: Küçük resim veri biçimi.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Küçük resmin yüksekliğini piksel cinsinden alır veya ayarlar.

Değer: Küçük resim yüksekliği.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar.

Değer: Kaynak için benzersiz tanımlayıcı.

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


JPEG seçeneklerini alır veya ayarlar. Yalnızca küçük resim kaynağı JPEG dosya biçiminde kaydedildiğinde uygundur. RAW biçimi tanımlandığında bu seçenek etkisizdir.

Değer: JPEG seçenekleri.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Minimum gerekli psd sürümünü alır.

Değer: Minimum psd sürümü.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null ad iki bayt 0'dan oluşur).

Değer: Kaynak adı.

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


Düzlem sayısını alır veya ayarlar.

Değer: Küçük resim düzlemlerinin sayısı.

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Kaynak imzasını alır. Her zaman '8BIM' olmalıdır.

Değer: Kaynak imzası.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Veri dahil olmak üzere kaynak blok boyutunu bayt cinsinden alır.

Değer: Kaynak blok boyutu.

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


Sıkıştırma sonrası boyutu alır veya ayarlar. Tutarlılık kontrolü için kullanılır.

Değer: Sıkıştırma sonrası boyut.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


32-bit ARGB küçük resim verisini alır veya ayarlar.

Değer: 32-bit ARGB küçük resim verisi.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


Küçük resim verisini alır veya ayarlar.

Değer: Küçük resim verisi.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


Toplam veri boyutunu alır.

Değer: Toplam veri boyutu.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Küçük resmin genişliğini piksel cinsinden alır veya ayarlar.

Değer: Küçük resim genişliği.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


Satır genişliğini bayt cinsinden alır.

Değer: Satır genişliği bayt cinsinden.

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Kaynak bloğunu belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kaynak bloğunu kaydetmek için akış. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


Piksel başına bit sayısını alır veya ayarlar.

Değer: Küçük resim piksel başına bit sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Küçük resim veri formatını alır veya ayarlar.

Değer: Küçük resim veri biçimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Küçük resmin yüksekliğini piksel cinsinden alır veya ayarlar.

Değer: Küçük resim yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar.

Değer: Kaynak için benzersiz tanımlayıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


JPEG seçeneklerini alır veya ayarlar. Yalnızca küçük resim kaynağı JPEG dosya biçiminde kaydedildiğinde uygundur. RAW biçimi tanımlandığında bu seçenek etkisizdir.

Değer: JPEG seçenekleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Katman ve maske bilgilerini alır veya ayarlar.

Değer: Katman ve maske bilgileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null ad iki bayt 0'dan oluşur).

Değer: Kaynak adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


Düzlem sayısını alır veya ayarlar.

Değer: Küçük resim düzlemlerinin sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imza | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Kaynak blok durumunu alır veya ayarlar.

Değer: Kaynak blok durumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


32-bit ARGB küçük resim verisini alır veya ayarlar.

Değer: 32-bit ARGB küçük resim verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


Küçük resim verisini alır veya ayarlar.

Değer: Küçük resim verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Küçük resmin genişliğini piksel cinsinden alır veya ayarlar.

Değer: Küçük resim genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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


Kaynak değerlerini doğrular.

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

