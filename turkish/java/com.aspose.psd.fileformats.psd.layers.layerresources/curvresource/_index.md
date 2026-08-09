---
title: "CurvResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "Sınıf CurvResource."
type: docs
weight: 23
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class CurvResource extends AdjustmentLayerResource
```

Sınıf CurvResource. Eğriler Ayar Katmanı Kaynağı 1 bayt - eğriler kullanılıyorsa 0, haritada pikseller kullanılıyorsa 1; eğer 0 ise: 2 bayt - kısa. Varsayılan 1 4 bayt - int. Yalnızca son bayt bit ile kullanılır. İlk bit 1 kanal için, Dördüncü bit 4 kanal için örnek 2 bayt - kısa nokta sayısı 4 bayt \* nokta sayısı - eğri noktaları 2 kısa: ilk konum, ikinci yükseklik 4 bayt - kelime \"Crv \" 2 bayt - kısa varsayılan 4 (Eğriler için) 4 bayt - int. Varsayılan 1 4 bayt - nokta sayısı 4 bayt \* nokta sayısı - eğri noktaları 2 kısa: ilk konum, ikinci yükseklik 0-4 bayt - Dört için katlanmalı ön ek eğer 1 ise: 2 bayt - kısa. Varsayılan 1 4 bayt - int. Yalnızca son bayt kullanılır. Bir kanal bir bit içinde. İlk bit 1 kanal için, Dördüncü bit 4 kanal için örnek 256 \* değiştirilen kanal sayısı - 0-255 aralığında kanal değerleri 4 bayt - kelime \"Crv \" 2 bayt - kısa. Varsayılan 3 (haritada pikseller için) 4 bayt - int Kanal sayısı (2 + 256) bayt - kısa 2 kanal indeksi için, 256 0-255 aralığında kanal değerleri
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CurvResource(int maxChannelCount)](#CurvResource-int-) | Yeni bir [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource) sınıfının bir örneğini başlatır. |
| [CurvResource(byte[] bytes)](#CurvResource-byte---) | Yeni bir [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource) sınıfının bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB başlık sürümü |
| [PsbResourceSignature](#PsbResourceSignature) | PSB'ye özgü kaynak imzası. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD başlık sürümü |
| [ResourceSignature](#ResourceSignature) | Ortak kaynak imzası. |
| [TypeToolKey](#TypeToolKey) | Tip aracı bilgi anahtarı. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Girişim lisansı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveManager()](#getActiveManager--) | Etkin yöneticiyi alır. |
| [getChannelData(int channelIndex)](#getChannelData-int-) | Kanal verisini alır. |
| [getClass()](#getClass--) |  |
| [getCurveManager()](#getCurveManager--) | Eğri yöneticisini alır. |
| [getData()](#getData--) | Veriyi alır veya ayarlar. |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLength()](#getLength--) | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPsdVersion()](#getPsdVersion--) | Katman kaynağı için gereken minimum psd sürümünü alır. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [hashCode()](#hashCode--) |  |
| [isDataStoredDiscretely()](#isDataStoredDiscretely--) | Bu örneğin verisinin ayrık olarak depolanıp depolanmadığını gösteren değeri alır veya ayarlar. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Kaynağı belirtilen akış konteynerine kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setDataStoredDiscretely(boolean value)](#setDataStoredDiscretely-boolean-) | Bu örneğin verisinin ayrık olarak depolanıp depolanmadığını gösteren değeri alır veya ayarlar. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvResource(int maxChannelCount) {#CurvResource-int-}
```
public CurvResource(int maxChannelCount)
```


Yeni bir [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxChannelCount | int | Maksimum kanal sayısı. |

### CurvResource(byte[] bytes) {#CurvResource-byte---}
```
public CurvResource(byte[] bytes)
```


Yeni bir [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | byte[] | Baytlar. |

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


Tip aracı bilgi anahtarı.

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
### getActiveManager() {#getActiveManager--}
```
public final CurvesManager getActiveManager()
```


Etkin yöneticiyi alır.

**Returns:**
[CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) - Active manager
### getChannelData(int channelIndex) {#getChannelData-int-}
```
public final byte[] getChannelData(int channelIndex)
```


Kanal verisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| channelIndex | int | Kanalın indeksi. |

**Returns:**
byte[] - Kanal verisi
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurveManager() {#getCurveManager--}
```
public final CurvesManager getCurveManager()
```


Eğri yöneticisini alır.

**Returns:**
[CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) - [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) or [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager)
### getData() {#getData--}
```
public final byte[] getData()
```


Veriyi alır veya ayarlar.

Değer: Veri.

**Returns:**
byte[]
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
### isDataStoredDiscretely() {#isDataStoredDiscretely--}
```
public final boolean isDataStoredDiscretely()
```


Bu örneğin verisinin ayrık olarak depolanıp depolanmadığını gösteren değeri alır veya ayarlar.

Değer:  true  bu örnek veri ayrık olarak depolanıyorsa; aksi takdirde,  false .

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

### setDataStoredDiscretely(boolean value) {#setDataStoredDiscretely-boolean-}
```
public final void setDataStoredDiscretely(boolean value)
```


Bu örneğin verisinin ayrık olarak depolanıp depolanmadığını gösteren değeri alır veya ayarlar.

Değer:  true  bu örnek veri ayrık olarak depolanıyorsa; aksi takdirde,  false .

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

