---
title: "PattResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "Sınıf PattResource."
type: docs
weight: 66
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class PattResource extends LayerResource
```

PattResource sınıfı. Desen verisi içeren kaynak.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PattResource()](#PattResource--) | Yeni bir [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) sınıfının bir örneğini başlatır. |
| [PattResource(int key, PattResourceData[] patterns)](#PattResource-int-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---) | Yeni bir [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) sınıfının bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB başlık sürümü |
| [PsbResourceSignature](#PsbResourceSignature) | PSB'ye özgü kaynak imzası. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD başlık sürümü |
| [ResourceSignature](#ResourceSignature) | Ortak kaynak imzası. |
| [TypeToolKey](#TypeToolKey) | 8-bit için 'Patt' tip araç bilgi anahtarı. |
| [TypeToolKey2](#TypeToolKey2) | 16-bit için 'Pat2' tip araç bilgi anahtarı. |
| [TypeToolKey3](#TypeToolKey3) | 32-bit için 'Pat3' tip araç bilgi anahtarı. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Girişim lisansı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addNewPattResourceData_internalized(PattResource resource)](#addNewPattResourceData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Patt kaynağını varsayılan verilerle günceller. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. |
| [createDefaultNotEmptyResource_internalized(int bitDepth)](#createDefaultNotEmptyResource-internalized-int-) | Varsayılan boş olmayan kaynağı oluşturur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLength()](#getLength--) | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [getPatterns()](#getPatterns--) | Desen verilerini alır veya ayarlar; |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPsdVersion()](#getPsdVersion--) | Katman kaynağı için gereken minimum psd sürümünü alır. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Kaynak blok verisini kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [setPatterns(PattResourceData[] value)](#setPatterns-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---) | Desen verilerini alır veya ayarlar; |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [updateOrAddPattern_internalized(IPatternFillSettings patternSettings)](#updateOrAddPattern-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings-) | Desen veri öğesini arar ve yenisiyle günceller, aksi takdirde yeni öğeyi dizinin sonuna ekler. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResource() {#PattResource--}
```
public PattResource()
```


Yeni bir [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) sınıfının bir örneğini başlatır.

### PattResource(int key, PattResourceData[] patterns) {#PattResource-int-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---}
```
public PattResource(int key, PattResourceData[] patterns)
```


Yeni bir [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | int | Kaynak türü anahtarı. |
| patterns | [PattResourceData\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Desen verileri. |

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


8-bit için 'Patt' tip araç bilgi anahtarı.

### TypeToolKey2 {#TypeToolKey2}
```
public static final int TypeToolKey2
```


16-bit için 'Pat2' tip araç bilgi anahtarı.

### TypeToolKey3 {#TypeToolKey3}
```
public static final int TypeToolKey3
```


32-bit için 'Pat3' tip araç bilgi anahtarı.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Girişim lisansı.

### addNewPattResourceData_internalized(PattResource resource) {#addNewPattResourceData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public static void addNewPattResourceData_internalized(PattResource resource)
```


Patt kaynağını varsayılan verilerle günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) | Kaynak. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. Şu anda bazı kaynaklar tanınmıyor, ancak kaydetme sırasında davranışlarını değiştiren PSB'ye özgü kaynakların tam listesine sahibiz. Bu yüzden bunu en azından UnknownResource içinde kontrol etmemiz gerekiyor.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | int | Anahtar. |

### createDefaultNotEmptyResource_internalized(int bitDepth) {#createDefaultNotEmptyResource-internalized-int-}
```
public static PattResource createDefaultNotEmptyResource_internalized(int bitDepth)
```


Varsayılan boş olmayan kaynağı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitDepth | int |  |

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - Created [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource)
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
### getPatterns() {#getPatterns--}
```
public final PattResourceData[] getPatterns()
```


Desen verilerini alır veya ayarlar;

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData[]
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


Kaynak blok verisini kaydeder.

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

### setPatterns(PattResourceData[] value) {#setPatterns-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---}
```
public final void setPatterns(PattResourceData[] value)
```


Desen verilerini alır veya ayarlar;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PattResourceData\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) |  |

### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir String döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir dize.
### updateOrAddPattern_internalized(IPatternFillSettings patternSettings) {#updateOrAddPattern-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings-}
```
public final void updateOrAddPattern_internalized(IPatternFillSettings patternSettings)
```


Desen veri öğesini arar ve yenisiyle günceller, aksi takdirde yeni öğeyi dizinin sonuna ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| patternSettings | [IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings) | Desen öğesini güncellemek için desen ayarları nesnesi. |

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

