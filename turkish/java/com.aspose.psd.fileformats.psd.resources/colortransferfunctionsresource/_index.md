---
title: "ColorTransferFunctionsResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "Renk aktarım kaynağı"
type: docs
weight: 15
url: /tr/java/com.aspose.psd.fileformats.psd.resources/colortransferfunctionsresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class ColorTransferFunctionsResource extends ResourceBlock
```

Renk aktarım kaynağı
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ColorTransferFunctionsResource()](#ColorTransferFunctionsResource--) | Yeni bir [ColorTransferFunctionsResource](../../com.aspose.psd.fileformats.psd.resources/colortransferfunctionsresource) sınıfının örneğini başlatır. |
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
| [getColorTransferData()](#getColorTransferData--) | Renk aktarım verisini alır veya ayarlar. |
| [getDataSize()](#getDataSize--) | Kaynak veri boyutunu bayt cinsinden alır. |
| [getID()](#getID--) | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| [getMinimalVersion()](#getMinimalVersion--) | Minimum gerekli PSD sürümünü alır. |
| [getName()](#getName--) | Kaynak adını alır veya ayarlar. |
| [getSignature()](#getSignature--) | Kaynak imzasını alır. |
| [getSize()](#getSize--) | Veri dahil olmak üzere kaynak blok boyutunu bayt cinsinden alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Kaynak bloğunu belirtilen akışa kaydeder. |
| [setColorTransferData(byte[] value)](#setColorTransferData-byte---) | Renk aktarım verisini alır veya ayarlar. |
| [setID(short value)](#setID-short-) | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Katman ve maske bilgilerini alır veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Kaynak adını alır veya ayarlar. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Kaynak blok durumunu alır veya ayarlar. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Kaynak değerlerini doğrular. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorTransferFunctionsResource() {#ColorTransferFunctionsResource--}
```
public ColorTransferFunctionsResource()
```


Yeni bir [ColorTransferFunctionsResource](../../com.aspose.psd.fileformats.psd.resources/colortransferfunctionsresource) sınıfının örneğini başlatır.

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
### getColorTransferData() {#getColorTransferData--}
```
public final byte[] getColorTransferData()
```


Renk aktarım verisini alır veya ayarlar.

Değer: Renk aktarım verisi.

**Returns:**
byte[]
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Kaynak veri boyutunu bayt cinsinden alır.

Değer: Kaynak veri boyutu.

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

### setColorTransferData(byte[] value) {#setColorTransferData-byte---}
```
public final void setColorTransferData(byte[] value)
```


Renk aktarım verisini alır veya ayarlar.

Değer: Renk aktarım verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

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

