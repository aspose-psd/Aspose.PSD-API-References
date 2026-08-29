---
title: "LiFdDataSource"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD dosyasında gömülü bir dosya hakkında bilgi içeren liFD veri kaynağı sınıfını tanımlar."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFdDataSource extends LinkDataSource
```

PSD Dosyasında gömülü bir dosya hakkında bilgi içeren liFD veri kaynağı sınıfını tanımlar. Bu, Adobe® Photoshop® dosyalarını değiştirmeye yardımcı olan PSD Dosya Formatı Manipülasyonu API'sinin bir parçasıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LiFdDataSource()](#LiFdDataSource--) | Yeni bir [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) sınıfı örneği başlatır. |
| [LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | Yeni bir [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | Tanımlayıcı sürümü. |
| [LatestVersion_internalized](#LatestVersion-internalized) | Bağlantı veri kaynağının mevcut en son sürümü |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | Beklenmeyen bağlantı veri kaynağı türü değeri |
| [ZeroChar_internalized](#ZeroChar-internalized) | Sıfır karakteri |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | PSD varlığının kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getAssetModTime()](#getAssetModTime--) | Adobe® Photoshop® \\u0421\\u0421 Kütüphaneleri varlıkları için varlık değiştirilme zamanını alır veya ayarlar. |
| [getChildDocId()](#getChildDocId--) | Adobe® Photoshop® kaynağının Lnk2 / LnkE içinde liFE veya liFD veri kaynağındaki alt belge tanımlayıcısını alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Kaynak sınıf kimliğini alır veya ayarlar. |
| [getClassName_internalized()](#getClassName-internalized--) | Kaynak sınıf adını alır veya ayarlar. |
| [getCompId()](#getCompId--) | Hiçbiri seçilmemişse -1 olacak şekilde, alt belge için şu anda seçili olan bileşenin kimliğini alır veya ayarlar. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | ContentID özelliğini alır veya ayarlar. |
| [getData()](#getData--) | PSD dosyasındaki gömülü akıllı nesne verisini alır veya ayarlar. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Gömülü verinin uzunluğunu alır. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Bağlantı kaynak verisinin uzunluğunu alır. |
| [getFileCreator()](#getFileCreator--) | PSD formatındaki LnkE / Lnk2 kaynağında dosya oluşturucusunu alır veya ayarlar. |
| [getFileType()](#getFileType--) | Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağlandığı gömülü veya harici dosyanın türünü alır veya ayarlar. |
| [getItems_internalized()](#getItems-internalized--) | Kaynak özelliklerini tanımlayan OSTypeStructure dizisini alır veya ayarlar. |
| [getLength()](#getLength--) | Bağlantı veri kaynağının uzunluğunu bayt olarak alır. |
| [getOriginalCompId()](#getOriginalCompId--) | Alt belge için şu anda seçili olan Comp'in özgün kimliğini alır; hiçbiri seçilmemişse -1 olur. |
| [getOriginalFileName()](#getOriginalFileName--) | Adobe® Photoshop® global bağlantı kaynağındaki veri kaynağının özgün dosya adını alır. |
| [getType()](#getType--) | Adobe® Photoshop® global bağlantı veri kaynağı türünü alır; aşağıdakilerden biri olabilir veya hiçbiri: PSD Lnk2Resource ile eşleşen gömülü bağlantılı dosya liFD, PSD LnkeResource ile eşleşen harici bağlantılı dosya liFE, bağlantılı dosya takma adı liFA |
| [getUniqueId()](#getUniqueId--) | PSD bağlantı kaynağındaki veri kaynağının küresel benzersiz tanımlayıcısını alır. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Öğeler OSTypeStructures özelliklerinden önce gelen bilinmeyen veriyi alır veya ayarlar. |
| [getVersion()](#getVersion--) | PSD LnkE / Lnk2 kaynağındaki veri kaynağının sürümünü alır. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Bu bağlantı veri kaynağının dosya açık tanımlayıcısına (CompId ve OriginalCompId) sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Bu PSD bağlantı veri kaynağının Adobe® Photoshop® \u0421\u0421 Kütüphane öğesine bağlanıp bağlanmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Bağlantı veri kaynağı blok verisini kaydeder. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | PSD varlığının kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Adobe® Photoshop® \\u0421\\u0421 Kütüphaneleri varlıkları için varlık değiştirilme zamanını alır veya ayarlar. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Adobe® Photoshop® kaynağının Lnk2 / LnkE içinde liFE veya liFD veri kaynağındaki alt belge tanımlayıcısını alır veya ayarlar. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Kaynak sınıf kimliğini alır veya ayarlar. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Kaynak sınıf adını alır veya ayarlar. |
| [setCompId(int value)](#setCompId-int-) | Hiçbiri seçilmemişse -1 olacak şekilde, alt belge için şu anda seçili olan bileşenin kimliğini alır veya ayarlar. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | ContentID özelliğini alır veya ayarlar. |
| [setData(byte[] value)](#setData-byte---) | PSD dosyasındaki gömülü akıllı nesne verisini alır veya ayarlar. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | PSD formatındaki LnkE / Lnk2 kaynağında dosya oluşturucusunu alır veya ayarlar. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Bu bağlantı veri kaynağının dosya açık tanımlayıcısına (CompId ve OriginalCompId) sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağlandığı gömülü veya harici dosyanın türünü alır veya ayarlar. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Kaynak özelliklerini tanımlayan OSTypeStructure dizisini alır veya ayarlar. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Bu PSD bağlantı veri kaynağının Adobe® Photoshop® \u0421\u0421 Kütüphane öğesine bağlanıp bağlanmadığını gösteren bir değeri alır. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Alt belge için şu anda seçili olan Comp'in özgün kimliğini alır; hiçbiri seçilmemişse -1 olur. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Adobe® Photoshop® global bağlantı kaynağındaki veri kaynağının özgün dosya adını alır. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Özellik değerini tip yapısına göre ayarlar. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | PSD bağlantı kaynağındaki veri kaynağının küresel benzersiz tanımlayıcısını alır. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Öğeler OSTypeStructures özelliklerinden önce gelen bilinmeyen veriyi alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFdDataSource() {#LiFdDataSource--}
```
public LiFdDataSource()
```


Yeni bir [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) sınıfı örneği başlatır.

### LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


Yeni bir [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| version | int | Sürüm. |
| uniqueId | java.util.UUID | Benzersiz tanımlayıcı. |
| originalFileName | java.lang.String | Özgün dosyanın adı. |
| fileType | java.lang.String | Dosyanın türü. |
| fileCreator | java.lang.String | Dosya oluşturucu. |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


Tanımlayıcı sürümü.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


Bağlantı veri kaynağının mevcut en son sürümü

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


Beklenmeyen bağlantı veri kaynağı türü değeri

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Sıfır karakteri

### create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFdDataSource create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| version | int |  |
| guid | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource)
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
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


PSD varlığının kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. Adobe® Photoshop® \\u0421\\u0421 Kütüphaneleri varlıkları için varlık kilitli durumu.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Adobe® Photoshop® \\u0421\\u0421 Kütüphaneleri varlıkları için varlık değiştirilme zamanını alır veya ayarlar.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Adobe® Photoshop® kaynağının Lnk2 / LnkE içinde liFE veya liFD veri kaynağındaki alt belge tanımlayıcısını alır veya ayarlar.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Kaynak sınıf kimliğini alır veya ayarlar.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Kaynak sınıf adını alır veya ayarlar.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Alt belge için şu anda seçili olan comp'in kimliğini alır veya ayarlar; hiçbir şey seçili değilse -1 olur. Comp'ler, tasarımcıların oluşturabileceği bir sayfa düzeninin bileşimleridir. Katman comp'lerini kullanarak, tek bir Adobe® Photoshop® dosyasında bir düzenin birden çok sürümünü oluşturabilir, yönetebilir ve görüntüleyebilirsiniz. Bir layer comp, Layers panelinin bir durumunun anlık görüntüsüdür. Layer comp'ler üç tür katman seçeneğini kaydeder ancak bu özellik Smart Objects için Layer Comp seçim tanımlayıcısını alır. Smart Objects'taki layer comp'ler

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


ContentID özelliğini alır veya ayarlar. Bu özelliğin değeri yalnızca Version >= 8 olduğunda okunur ve kaydedilir.

**Returns:**
java.lang.String
### getData() {#getData--}
```
public final byte[] getData()
```


PSD dosyasındaki gömülü akıllı nesne verisini alır veya ayarlar.

Değer: Gömülü akıllı nesne verisi.

**Returns:**
byte[]
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Gömülü verinin uzunluğunu alır.

Değer: Gömülü verinin uzunluğu.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Bağlantı kaynak verisinin uzunluğunu alır.

**Returns:**
long - Kaynak veri uzunluğu.
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


PSD formatındaki LnkE / Lnk2 kaynağında dosya oluşturucusunu alır veya ayarlar.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağlandığı gömülü veya harici dosyanın türünü alır veya ayarlar.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Kaynak özelliklerini tanımlayan OSTypeStructure dizisini alır veya ayarlar.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Bağlantı veri kaynağının uzunluğunu bayt olarak alır.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Alt belge için şu anda seçili olan Comp'in orijinal kimliğini alır; hiçbir şey seçili değilse -1 olur. Bu özellik Smart Objects için orijinal layer Comp seçim tanımlayıcısını alır. Smart Objects'taki layer comp'ler

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Adobe® Photoshop® global bağlantı kaynağındaki veri kaynağının özgün dosya adını alır.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Adobe® Photoshop® global bağlantı veri kaynağı türünü alır; aşağıdakilerden biri olabilir veya hiçbiri: PSD Lnk2Resource ile eşleşen gömülü bağlantılı dosya liFD, PSD LnkeResource ile eşleşen harici bağlantılı dosya liFE, bağlantılı dosya takma adı liFA

Değer: PSD bağlantı veri kaynağı türü.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


PSD bağlantı kaynağındaki veri kaynağının küresel benzersiz tanımlayıcısını alır.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Öğeler OSTypeStructures özelliklerinden önce gelen bilinmeyen veriyi alır veya ayarlar.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


PSD LnkE / Lnk2 kaynağındaki veri kaynağının sürümünü alır.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Bu bağlantı veri kaynağının dosya açık tanımlayıcısına (CompId ve OriginalCompId) sahip olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek dosya açık tanımlayıcısına sahipse; aksi takdirde,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


Bu PSD bağlantı veri kaynağının Adobe® Photoshop® \u0421\u0421 Kütüphane öğesine bağlanıp bağlanmadığını gösteren bir değeri alır.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


Bağlantı veri kaynağı blok verisini kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


PSD varlığının kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. Adobe® Photoshop® \\u0421\\u0421 Kütüphaneleri varlıkları için varlık kilitli durumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Adobe® Photoshop® \\u0421\\u0421 Kütüphaneleri varlıkları için varlık değiştirilme zamanını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Adobe® Photoshop® kaynağının Lnk2 / LnkE içinde liFE veya liFD veri kaynağındaki alt belge tanımlayıcısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Kaynak sınıf kimliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Kaynak sınıf adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Alt belge için şu anda seçili olan comp'in kimliğini alır veya ayarlar; hiçbir şey seçili değilse -1 olur. Comp'ler, tasarımcıların oluşturabileceği bir sayfa düzeninin bileşimleridir. Katman comp'lerini kullanarak, tek bir Adobe® Photoshop® dosyasında bir düzenin birden çok sürümünü oluşturabilir, yönetebilir ve görüntüleyebilirsiniz. Bir layer comp, Layers panelinin bir durumunun anlık görüntüsüdür. Layer comp'ler üç tür katman seçeneğini kaydeder ancak bu özellik Smart Objects için Layer Comp seçim tanımlayıcısını alır. Smart Objects'taki layer comp'ler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


ContentID özelliğini alır veya ayarlar. Bu özelliğin değeri yalnızca Version >= 8 olduğunda okunur ve kaydedilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


PSD dosyasındaki gömülü akıllı nesne verisini alır veya ayarlar.

Değer: Gömülü akıllı nesne verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


PSD formatındaki LnkE / Lnk2 kaynağında dosya oluşturucusunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Bu bağlantı veri kaynağının dosya açık tanımlayıcısına (CompId ve OriginalCompId) sahip olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek dosya açık tanımlayıcısına sahipse; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağlandığı gömülü veya harici dosyanın türünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Kaynak özelliklerini tanımlayan OSTypeStructure dizisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Bu PSD bağlantı veri kaynağının Adobe® Photoshop® \u0421\u0421 Kütüphane öğesine bağlanıp bağlanmadığını gösteren bir değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Alt belge için şu anda seçili olan Comp'in orijinal kimliğini alır; hiçbir şey seçili değilse -1 olur. Bu özellik Smart Objects için orijinal layer Comp seçim tanımlayıcısını alır. Smart Objects'taki layer comp'ler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Adobe® Photoshop® global bağlantı kaynağındaki veri kaynağının özgün dosya adını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Özellik değerini tip yapısına göre ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Yapı. |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


PSD bağlantı kaynağındaki veri kaynağının küresel benzersiz tanımlayıcısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Öğeler OSTypeStructures özelliklerinden önce gelen bilinmeyen veriyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

