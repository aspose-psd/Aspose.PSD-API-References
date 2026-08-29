---
title: "VersionInfoResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "Sürüm Bilgisi kaynağı"
type: docs
weight: 41
url: /tr/java/com.aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class VersionInfoResource extends ResourceBlock
```

Sürüm Bilgisi kaynağı
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VersionInfoResource()](#VersionInfoResource--) | Yeni bir [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource) sınıfının örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady'ın kaynak imzası. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Normal Photoshop kaynak imzası. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Kaynak veri boyutunu bayt cinsinden alır. |
| [getFileVersion()](#getFileVersion--) | Dosya sürümünü alır veya ayarlar. |
| [getID()](#getID--) | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| [getMinimalVersion()](#getMinimalVersion--) | Minimum gerekli PSD sürümünü alır. |
| [getName()](#getName--) | Kaynak adını alır veya ayarlar. |
| [getReaderName()](#getReaderName--) | Okuyucunun adını alır veya ayarlar. |
| [getSignature()](#getSignature--) | Kaynak imzasını alır. |
| [getSize()](#getSize--) | Veri dahil olmak üzere kaynak blok boyutunu bayt cinsinden alır. |
| [getVersion()](#getVersion--) | Sürümü alır veya ayarlar. |
| [getWriterName()](#getWriterName--) | Yazıcının adını alır veya ayarlar. |
| [hasRealMergedData()](#hasRealMergedData--) | Bu örneğin gerçek birleştirilmiş veri içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Kaynak bloğunu belirtilen akışa kaydeder. |
| [setFileVersion(long value)](#setFileVersion-long-) | Dosya sürümünü alır veya ayarlar. |
| [setID(short value)](#setID-short-) | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Katman ve maske bilgilerini alır veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Kaynak adını alır veya ayarlar. |
| [setReaderName(String value)](#setReaderName-java.lang.String-) | Okuyucunun adını alır veya ayarlar. |
| [setRealMergedData(boolean value)](#setRealMergedData-boolean-) | Bu örneğin gerçek birleştirilmiş veri içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Kaynak blok durumunu alır veya ayarlar. |
| [setVersion(long value)](#setVersion-long-) | Sürümü alır veya ayarlar. |
| [setWriterName(String value)](#setWriterName-java.lang.String-) | Yazıcının adını alır veya ayarlar. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Kaynak değerlerini doğrular. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VersionInfoResource() {#VersionInfoResource--}
```
public VersionInfoResource()
```


Yeni bir [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource) sınıfının örneğini başlatır.

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
### getFileVersion() {#getFileVersion--}
```
public final long getFileVersion()
```


Dosya sürümünü alır veya ayarlar.

Değer: Dosya sürümü.

**Returns:**
long
### getID() {#getID--}
```
public final short getID()
```


Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar.

Değer: Kaynak için benzersiz tanımlayıcı.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Minimum gerekli PSD sürümünü alır.

Değer: Minimum PSD sürümü.

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
### getReaderName() {#getReaderName--}
```
public final String getReaderName()
```


Okuyucunun adını alır veya ayarlar.

Değer: Okuyucu adı.

**Returns:**
java.lang.String
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
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Sürümü alır veya ayarlar.

Değer: Sürüm.

**Returns:**
long
### getWriterName() {#getWriterName--}
```
public final String getWriterName()
```


Yazıcının adını alır veya ayarlar.

Değer: Yazıcı adı.

**Returns:**
java.lang.String
### hasRealMergedData() {#hasRealMergedData--}
```
public final boolean hasRealMergedData()
```


Bu örneğin gerçek birleştirilmiş veri içerip içermediğini gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek gerçek birleştirilmiş veri içeriyorsa; aksi takdirde,  false .

**Returns:**
boolean
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

### setFileVersion(long value) {#setFileVersion-long-}
```
public final void setFileVersion(long value)
```


Dosya sürümünü alır veya ayarlar.

Değer: Dosya sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

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

### setReaderName(String value) {#setReaderName-java.lang.String-}
```
public final void setReaderName(String value)
```


Okuyucunun adını alır veya ayarlar.

Değer: Okuyucu adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setRealMergedData(boolean value) {#setRealMergedData-boolean-}
```
public final void setRealMergedData(boolean value)
```


Bu örneğin gerçek birleştirilmiş veri içerip içermediğini gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek gerçek birleştirilmiş veri içeriyorsa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

### setVersion(long value) {#setVersion-long-}
```
public final void setVersion(long value)
```


Sürümü alır veya ayarlar.

Değer: Sürüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setWriterName(String value) {#setWriterName-java.lang.String-}
```
public final void setWriterName(String value)
```


Yazıcının adını alır veya ayarlar.

Değer: Yazıcı adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

