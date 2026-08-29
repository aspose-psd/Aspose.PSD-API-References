---
title: "LspfResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "Katman korumalı ayarlar"
type: docs
weight: 57
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LspfResource extends LayerResource
```

Katman korumalı ayarlar
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LspfResource(byte[] data)](#LspfResource-byte---) | Yeni bir [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) sınıfı örneği başlatır. |
| [LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)](#LspfResource-boolean-boolean-boolean-) | Yeni bir [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) sınıfı örneği başlatır. |
| [LspfResource()](#LspfResource--) | Yeni bir [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB başlık sürümü |
| [PsbResourceSignature](#PsbResourceSignature) | PSB'ye özgü kaynak imzası. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD başlık sürümü |
| [ResourceSignature](#ResourceSignature) | Ortak kaynak imzası. |
| [TypeToolKey](#TypeToolKey) | Tür aracı bilgi anahtarı 1819504742 |
| [ventureLicense_internalized](#ventureLicense-internalized) | Girişim lisansı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLength()](#getLength--) | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [getLockType()](#getLockType--) | Kilit tipini alır veya ayarlar. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPsdVersion()](#getPsdVersion--) | Katman kaynağı için gereken minimum psd sürümünü alır. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [hashCode()](#hashCode--) |  |
| [isCompositeProtected()](#isCompositeProtected--) | Bu örneğin birleşik korumalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isPositionProtected()](#isPositionProtected--) | Bu örneğin konum korumalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [isTransparencyProtected()](#isTransparencyProtected--) | Bu örneğin şeffaflık korumalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Kaynağı belirtilen akış konteynerine kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setCompositeProtected(boolean value)](#setCompositeProtected-boolean-) | Bu örneğin birleşik korumalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [setLockType(int value)](#setLockType-int-) | Kilit tipini alır veya ayarlar. |
| [setPositionProtected(boolean value)](#setPositionProtected-boolean-) | Bu örneğin konum korumalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setTransparencyProtected(boolean value)](#setTransparencyProtected-boolean-) | Bu örneğin şeffaflık korumalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LspfResource(byte[] data) {#LspfResource-byte---}
```
public LspfResource(byte[] data)
```


Yeni bir [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) sınıfı örneği başlatır. Özel veya bilinmeyen değer ile.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Kaynak verisi. |

### LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected) {#LspfResource-boolean-boolean-boolean-}
```
public LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)
```


Yeni bir [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isTransparencyProtected | boolean | eğer true [şeffaflık korumalı] olarak ayarlanır. |
| isCompositeProtected | boolean | eğer true [birleşik korumalı] olarak ayarlanır. |
| isPositionProtected | boolean | eğer true [konum korumalı] olarak ayarlanır. |

### LspfResource() {#LspfResource--}
```
public LspfResource()
```


Yeni bir [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) sınıfı örneği başlatır.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB başlık sürümü

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB'ye özgü kaynak imzası.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD başlık sürümü

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Ortak kaynak imzası.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Tür aracı bilgi anahtarı 1819504742

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Girişim lisansı.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. Şu anda bazı kaynaklar tanınmıyor, ancak kaydetme sırasında davranışlarını değiştiren PSB'ye özgü kaynakların tam listesine sahibiz. Bu yüzden bunu en azından UnknownResource içinde kontrol etmemiz gerekiyor.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | int | Anahtar. |

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
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Üst bilgiyi alır veya ayarlar.

Değer: Başlık.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


Katman kaynağı anahtarını alır.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Katman kaynağı uzunluğunu bayt cinsinden alır.

**Returns:**
int
### getLockType() {#getLockType--}
```
public final int getLockType()
```


Kilit tipini alır veya ayarlar.

Değer: Kilit tipi.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Önek uzunluğunu alır. Varsayılan değer 8BIM kaynakları için 12, 8B64 için 16'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| psdVersion | int | PSD sürümü. |

**Returns:**
int - Önek Uzunluğu.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Katman kaynağı için gereken minimum psd sürümünü alır. 0, herhangi bir kısıtlama olmadığını gösterir.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Katman kaynağı imzasını alır.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompositeProtected() {#isCompositeProtected--}
```
public final boolean isCompositeProtected()
```


Bu örneğin birleşik korumalı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: true eğer bu örnek birleşik korumalıysa; aksi takdirde false.

**Returns:**
boolean
### isPositionProtected() {#isPositionProtected--}
```
public final boolean isPositionProtected()
```


Bu örneğin konum korumalı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: true eğer bu örnek konum korumalıysa; aksi takdirde false.

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Kaynağın PSB'ye özgü olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | int | Kaynak anahtarı. |

**Returns:**
boolean -  true  eğer kaynak PSB'ye özgüyse; aksi takdirde,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır.

Değer:  true  eğer bu örnek kaynak PSB'ye özgüyse; aksi takdirde,  false .

**Returns:**
boolean
### isTransparencyProtected() {#isTransparencyProtected--}
```
public final boolean isTransparencyProtected()
```


Bu örneğin şeffaflık korumalı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer bu örnek şeffaflık korumalıysa; aksi takdirde,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Kaynağı belirtilen akış konteynerine kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psdVersion | int | PSD sürümü. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Özel kaynak başlığını kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |
| imza | int | İmza. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |
| imza | int | İmza. |
| isLengthLong | boolean | eğer  true  olarak ayarlanırsa uzunluk uzun olur. |

### setCompositeProtected(boolean value) {#setCompositeProtected-boolean-}
```
public final void setCompositeProtected(boolean value)
```


Bu örneğin birleşik korumalı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: true eğer bu örnek birleşik korumalıysa; aksi takdirde false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Üst bilgiyi alır veya ayarlar.

Değer: Başlık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Kilit tipini alır veya ayarlar.

Değer: Kilit tipi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setPositionProtected(boolean value) {#setPositionProtected-boolean-}
```
public final void setPositionProtected(boolean value)
```


Bu örneğin konum korumalı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: true eğer bu örnek konum korumalıysa; aksi takdirde false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setTransparencyProtected(boolean value) {#setTransparencyProtected-boolean-}
```
public final void setTransparencyProtected(boolean value)
```


Bu örneğin şeffaflık korumalı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer bu örnek şeffaflık korumalıysa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir String döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir dize.
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

