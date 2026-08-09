---
title: "LnkeResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD formatındaki görüntüde harici bağlı dosyalar veya varlıklar hakkında bilgi içeren LnkeResource sınıfını tanımlar."
type: docs
weight: 17
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkresource)
```
public class LnkeResource extends LinkResource
```

LnkeResource sınıfını tanımlar; bu sınıf PSD formatı görüntüsündeki dış bağlantılı dosyalar veya varlıklar hakkında bilgi içerir. Bağlantı kaynağı, dizinleyici aracılığıyla erişilebilen birkaç [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) örneği içerebilir. Bu, Adobe® Photoshop® dosyalarını programlı olarak değiştirmeye yardımcı olan PSD Dosya Formatı Manipülasyonu API'sinin bir parçasıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LnkeResource()](#LnkeResource--) | Yeni bir [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) sınıfı örneği başlatır. |
| [LnkeResource(LinkDataSource[] dataSources)](#LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource---) | Yeni bir [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CannotAddTheDataSourceMessage_internalized](#CannotAddTheDataSourceMessage-internalized) | 'cannot add the data source' mesajı |
| [DataSourceTypeIsWrongMessage_internalized](#DataSourceTypeIsWrongMessage-internalized) | 'The data source type is wrong' mesajı |
| [LengthOSourceLengthField](#LengthOSourceLengthField) | Veri kaynağı uzunluk alanının uzunluğu. |
| [LengthOfResourceLengthField](#LengthOfResourceLengthField) | Toplam kaynak uzunluk alanının uzunluğu. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB başlık sürümü |
| [PsbResourceSignature](#PsbResourceSignature) | PSB'ye özgü kaynak imzası. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD başlık sürümü |
| [ResourceSignature](#ResourceSignature) | Ortak kaynak imzası. |
| [TypeToolKey](#TypeToolKey) | Tip aracı bilgi anahtarı. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Girişim lisansı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addDataSource_internalized(LinkDataSource dataSource)](#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Veri kaynağını ekler. |
| [addOrReplaceDataSource_internalized(LinkDataSource dataSource)](#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Veri kaynağını ekler veya değiştirir. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSourceCount()](#getDataSourceCount--) | Dizinleyici ile erişilebilen bağlantı veri kaynaklarının sayısını alır. |
| [getDataSources_internalized()](#getDataSources-internalized--) | LinkDataSource[] veri kaynakları dizisini alır. |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLength()](#getLength--) | PSD genel bağlantı kaynağı uzunluğunu bayt olarak alır. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPsdVersion()](#getPsdVersion--) | Katman kaynağı için gereken minimum psd sürümünü alır. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [getType_internalized()](#getType-internalized--) | PSD genel bağlantı kaynağı tipini alır veya ayarlar; bu tip aşağıdakilerden biri olabilir veya hiçbiri: Gömülü bağlantılı dosya liFD (Lnk2Resource ve Lnk3Resource ile eşleşir) Harici bağlantılı dosya liFE (LnkeResource ile eşleşir) Bağlantılı dosya takma adı liFA |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) alır. |
| [get_Item(UUID index)](#get-Item-java.util.UUID-) | Belirtilen indeksteki [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) öğesini alır; bu, bağlantı veri kaynağının benzersiz tanımlayıcısıdır. |
| [get_Item_internalized(System.Guid index)](#get-Item-internalized-com.aspose.ms.System.Guid-) |  |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | Bu bağlantı kaynağı örneğinin boş olup olmadığını gösteren bir değer alır. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeDataSource_internalized(System.Guid uniqueId)](#removeDataSource-internalized-com.aspose.ms.System.Guid-) | Bağlantı veri kaynağını kaldırır. |
| [replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Veri kaynağını değiştirir. |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Kaynak blok verisini kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LnkeResource() {#LnkeResource--}
```
public LnkeResource()
```


Yeni bir [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) sınıfı örneği başlatır.

### LnkeResource(LinkDataSource[] dataSources) {#LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource---}
```
public LnkeResource(LinkDataSource[] dataSources)
```


Yeni bir [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataSources | [LinkDataSource\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Veri kaynakları. |

### CannotAddTheDataSourceMessage_internalized {#CannotAddTheDataSourceMessage-internalized}
```
public static final String CannotAddTheDataSourceMessage_internalized
```


'cannot add the data source' mesajı

### DataSourceTypeIsWrongMessage_internalized {#DataSourceTypeIsWrongMessage-internalized}
```
public static final String DataSourceTypeIsWrongMessage_internalized
```


'The data source type is wrong' mesajı

### LengthOSourceLengthField {#LengthOSourceLengthField}
```
public static final int LengthOSourceLengthField
```


Veri kaynağı uzunluk alanının uzunluğu.

### LengthOfResourceLengthField {#LengthOfResourceLengthField}
```
public static final int LengthOfResourceLengthField
```


Toplam kaynak uzunluk alanının uzunluğu.

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

### addDataSource_internalized(LinkDataSource dataSource) {#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addDataSource_internalized(LinkDataSource dataSource)
```


Veri kaynağını ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Bağlantı veri kaynağı. |

### addOrReplaceDataSource_internalized(LinkDataSource dataSource) {#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addOrReplaceDataSource_internalized(LinkDataSource dataSource)
```


Veri kaynağını ekler veya değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Veri kaynağı. |

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
### getDataSourceCount() {#getDataSourceCount--}
```
public final int getDataSourceCount()
```


Dizinleyici ile erişilebilen bağlantı veri kaynaklarının sayısını alır.

Değer: Veri kaynağı sayısı.

**Returns:**
int
### getDataSources_internalized() {#getDataSources-internalized--}
```
public final LinkDataSource[] getDataSources_internalized()
```


LinkDataSource[] veri kaynakları dizisini alır.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource[]
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


PSD genel bağlantı kaynağı uzunluğunu bayt olarak alır.

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
### getType_internalized() {#getType-internalized--}
```
public final int getType_internalized()
```


PSD genel bağlantı kaynağı tipini alır veya ayarlar; bu tip aşağıdakilerden biri olabilir veya hiçbiri: Gömülü bağlantılı dosya liFD (Lnk2Resource ve Lnk3Resource ile eşleşir) Harici bağlantılı dosya liFE (LnkeResource ile eşleşir) Bağlantılı dosya takma adı liFA

Değer: PSD bağlantı kaynağı tipi.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final LiFeDataSource get_Item(int index)
```


Belirtilen dizindeki [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Dizin. Değer: [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |

**Returns:**
[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) - The [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) instance.
### get_Item(UUID index) {#get-Item-java.util.UUID-}
```
public final LinkDataSource get_Item(UUID index)
```


Belirtilen indeksteki [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) öğesini alır; bu, bağlantı veri kaynağının benzersiz tanımlayıcısıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | java.util.UUID | Dizin, bağlantı veri kaynağı benzersiz tanımlayıcısı olarak. Değer: [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource). |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### get_Item_internalized(System.Guid index) {#get-Item-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource get_Item_internalized(System.Guid index)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | com.aspose.ms.System.Guid |  |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Bu bağlantı kaynağı örneğinin boş olup olmadığını gösteren bir değer alır.

Değer: true eğer bu bağlantı kaynağı boşsa; aksi takdirde false.

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




### removeDataSource_internalized(System.Guid uniqueId) {#removeDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final void removeDataSource_internalized(System.Guid uniqueId)
```


Bağlantı veri kaynağını kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Benzersiz tanımlayıcı. |

### replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)
```


Veri kaynağını değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Benzersiz tanımlayıcı. |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Bağlantı veri kaynağı. |

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

