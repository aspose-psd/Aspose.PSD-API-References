---
title: "CgEdResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "Sınıf CgEdResource."
type: docs
weight: 18
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class CgEdResource extends AdjustmentLayerResource
```

Sınıf CgEdResource. İçerik Üreteci Ekstra Veri (Photoshop CS5)
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CgEdResource()](#CgEdResource--) | Yeni bir [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) sınıfının bir örneğini başlatır. |
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
| [getAuto()](#getAuto--) | Bu [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) nesnesinin otomatik olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getBrightness()](#getBrightness--) | Parlaklığı alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Kontrastı alır veya ayarlar. |
| [getData()](#getData--) | Veriyi alır veya ayarlar. |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLabColor()](#getLabColor--) | Bu [lab color] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
| [getLength()](#getLength--) | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [getMeanValueForBrightnessAndContrast()](#getMeanValueForBrightnessAndContrast--) | Parlaklık ve kontrast için ortalama değeri alır veya ayarlar. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPropertyValueByTypeStructure_internalized(String structureName)](#getPropertyValueByTypeStructure-internalized-java.lang.String-) | Özellik değerini tip yapısına göre alır. |
| [getPsdVersion()](#getPsdVersion--) | Katman kaynağı için gereken minimum psd sürümünü alır. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [getUseLegacy()](#getUseLegacy--) | Bu [use legacy] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
| [getVersion()](#getVersion--) | Sürümü alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Kaynağı belirtilen akış konteynerine kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setAuto(boolean value)](#setAuto-boolean-) | Bu [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) nesnesinin otomatik olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setBrightness(int value)](#setBrightness-int-) | Parlaklığı alır veya ayarlar. |
| [setContrast(int value)](#setContrast-int-) | Kontrastı alır veya ayarlar. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [setLabColor(boolean value)](#setLabColor-boolean-) | Bu [lab color] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
| [setMeanValueForBrightnessAndContrast(int value)](#setMeanValueForBrightnessAndContrast-int-) | Parlaklık ve kontrast için ortalama değeri alır veya ayarlar. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Özellik değerini tip yapısına göre ayarlar. |
| [setUseLegacy(boolean value)](#setUseLegacy-boolean-) | Bu [use legacy] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
| [setVersion(int value)](#setVersion-int-) | Sürümü alır veya ayarlar. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CgEdResource() {#CgEdResource--}
```
public CgEdResource()
```


Yeni bir [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) sınıfının bir örneğini başlatır. PSD formatı spesifikasyonu aşağıdaki açıklamayı içerir: 4 Tanımlayıcı Sürüm( = 16) Ek verilerin Değişken Uzunluklu Tanımlayıcısı Öneri: PS'nin eski sürümlerinde (CS5'ten önce) kullanılmayabilir.

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
### getAuto() {#getAuto--}
```
public final boolean getAuto()
```


Bu [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) nesnesinin otomatik olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  otomatik ise; aksi takdirde,  false .

**Returns:**
boolean
### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Parlaklığı alır veya ayarlar.

Değer: Parlaklık.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public final int getContrast()
```


Kontrastı alır veya ayarlar.

Değer: kontrast.

**Returns:**
int
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
### getLabColor() {#getLabColor--}
```
public final boolean getLabColor()
```


Bu [lab color] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  [lab color] kullanıldıysa; aksi takdirde,  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Katman kaynağı uzunluğunu bayt cinsinden alır.

**Returns:**
int
### getMeanValueForBrightnessAndContrast() {#getMeanValueForBrightnessAndContrast--}
```
public final int getMeanValueForBrightnessAndContrast()
```


Parlaklık ve kontrast için ortalama değeri alır veya ayarlar.

Değer: Parlaklık ve kontrast için ortalama değer.

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
### getPropertyValueByTypeStructure_internalized(String structureName) {#getPropertyValueByTypeStructure-internalized-java.lang.String-}
```
public final Object getPropertyValueByTypeStructure_internalized(String structureName)
```


Özellik değerini tip yapısına göre alır. Yalnızca UnitTests için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| structureName | java.lang.String | Yapının adı. |

**Returns:**
java.lang.Object - Kolay birim testleri için OSType yapısı
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
### getUseLegacy() {#getUseLegacy--}
```
public final boolean getUseLegacy()
```


Bu [use legacy] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [use legacy]; aksi takdirde,  false .

**Returns:**
boolean
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Sürümü alır veya ayarlar.

Değer: Sürüm.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setAuto(boolean value) {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```


Bu [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) nesnesinin otomatik olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  otomatik ise; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Parlaklığı alır veya ayarlar.

Değer: Parlaklık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Kontrastı alır veya ayarlar.

Değer: kontrast.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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

### setLabColor(boolean value) {#setLabColor-boolean-}
```
public final void setLabColor(boolean value)
```


Bu [lab color] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  [lab color] kullanıldıysa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setMeanValueForBrightnessAndContrast(int value) {#setMeanValueForBrightnessAndContrast-int-}
```
public final void setMeanValueForBrightnessAndContrast(int value)
```


Parlaklık ve kontrast için ortalama değeri alır veya ayarlar.

Değer: Parlaklık ve kontrast için ortalama değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Özellik değerini tip yapısına göre ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Yapı. |

### setUseLegacy(boolean value) {#setUseLegacy-boolean-}
```
public final void setUseLegacy(boolean value)
```


Bu [use legacy] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [use legacy]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Sürümü alır veya ayarlar.

Değer: Sürüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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

