---
title: "LiFeDataSource"
second_title: "Java için Aspose.PSD API Referansı"
description: "Harici bağlı dosya hakkında bilgi içeren LnkeDataSource sınıfını tanımlar."
type: docs
weight: 11
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFeDataSource extends LinkDataSource
```

LnkeDataSource sınıfını tanımlar; bu sınıf dış bağlantılı dosya hakkında bilgi içerir. Bu, Adobe® Photoshop® dosyalarını değiştirmeye yardımcı olan PSD Dosya Formatı Manipülasyonu API'sinin bir parçasıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LiFeDataSource()](#LiFeDataSource--) | Yeni bir [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) sınıf örneği başlatır. |
| [LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | Yeni bir [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) sınıf örneği başlatır. |
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
| [create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeStockId()](#getAdobeStockId--) | Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi AdobeStockId değerini alır veya ayarlar. |
| [getAdobeStockLicenseState()](#getAdobeStockLicenseState--) | Adobe® Photoshop® CC kütüphaneleri için mevcutsa Adobe stok lisansının durumunu alır. |
| [getAssetLockedState()](#getAssetLockedState--) | PSD varlığının kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getAssetModTime()](#getAssetModTime--) | Adobe® Photoshop® \\u0421\\u0421 Kütüphaneleri varlıkları için varlık değiştirilme zamanını alır veya ayarlar. |
| [getChildDocId()](#getChildDocId--) | Adobe® Photoshop® kaynağının Lnk2 / LnkE içinde liFE veya liFD veri kaynağındaki alt belge tanımlayıcısını alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Kaynak sınıf kimliğini alır veya ayarlar. |
| [getClassName_internalized()](#getClassName-internalized--) | Kaynak sınıf adını alır veya ayarlar. |
| [getCompId()](#getCompId--) | Hiçbiri seçilmemişse -1 olacak şekilde, alt belge için şu anda seçili olan bileşenin kimliğini alır veya ayarlar. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | ContentID özelliğini alır veya ayarlar. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Ek verinin uzunluğunu alır. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Bağlantı kaynak verisinin uzunluğunu alır. |
| [getDate()](#getDate--) | PSD LnkE kaynağının LiFE veri kaynağındaki dış dosyanın son yazma tarih ve saatini alır veya ayarlar. |
| [getDate_internalized()](#getDate-internalized--) |  |
| [getElementName()](#getElementName--) | Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi öğesi adını alır veya ayarlar. |
| [getElementRef()](#getElementRef--) | Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi öğesi referansını alır veya ayarlar. |
| [getFileCreator()](#getFileCreator--) | PSD formatındaki LnkE / Lnk2 kaynağında dosya oluşturucusunu alır veya ayarlar. |
| [getFileName()](#getFileName--) | PSD bağlantı kaynağındaki harici veya gömülü dosyanın adını alır veya ayarlar. |
| [getFileSize()](#getFileSize--) | PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın boyutunu alır veya ayarlar. |
| [getFileType()](#getFileType--) | Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağlandığı gömülü veya harici dosyanın türünü alır veya ayarlar. |
| [getFullPath()](#getFullPath--) | PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın tam yolunu alır veya ayarlar. |
| [getItems_internalized()](#getItems-internalized--) | Kaynak özelliklerini tanımlayan OSTypeStructure dizisini alır veya ayarlar. |
| [getLength()](#getLength--) | Bağlantı veri kaynağının uzunluğunu bayt olarak alır. |
| [getOriginalCompId()](#getOriginalCompId--) | Alt belge için şu anda seçili olan Comp'in özgün kimliğini alır; hiçbiri seçilmemişse -1 olur. |
| [getOriginalFileName()](#getOriginalFileName--) | Adobe® Photoshop® global bağlantı kaynağındaki veri kaynağının özgün dosya adını alır. |
| [getRelativePath()](#getRelativePath--) | PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın göreli yolunu alır veya ayarlar. |
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
| [setAdobeStockId(String value)](#setAdobeStockId-java.lang.String-) | Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi AdobeStockId değerini alır veya ayarlar. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | PSD varlığının kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Adobe® Photoshop® \\u0421\\u0421 Kütüphaneleri varlıkları için varlık değiştirilme zamanını alır veya ayarlar. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Adobe® Photoshop® kaynağının Lnk2 / LnkE içinde liFE veya liFD veri kaynağındaki alt belge tanımlayıcısını alır veya ayarlar. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Kaynak sınıf kimliğini alır veya ayarlar. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Kaynak sınıf adını alır veya ayarlar. |
| [setCompId(int value)](#setCompId-int-) | Hiçbiri seçilmemişse -1 olacak şekilde, alt belge için şu anda seçili olan bileşenin kimliğini alır veya ayarlar. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | ContentID özelliğini alır veya ayarlar. |
| [setDate(Date value)](#setDate-java.util.Date-) | PSD LnkE kaynağının LiFE veri kaynağındaki dış dosyanın son yazma tarih ve saatini alır veya ayarlar. |
| [setDate_internalized(System.DateTime value)](#setDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setElementName(String value)](#setElementName-java.lang.String-) | Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi öğesi adını alır veya ayarlar. |
| [setElementRef(String value)](#setElementRef-java.lang.String-) | Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi öğesi referansını alır veya ayarlar. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | PSD formatındaki LnkE / Lnk2 kaynağında dosya oluşturucusunu alır veya ayarlar. |
| [setFileName(String value)](#setFileName-java.lang.String-) | PSD bağlantı kaynağındaki harici veya gömülü dosyanın adını alır veya ayarlar. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Bu bağlantı veri kaynağının dosya açık tanımlayıcısına (CompId ve OriginalCompId) sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setFileSize(long value)](#setFileSize-long-) | PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın boyutunu alır veya ayarlar. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağlandığı gömülü veya harici dosyanın türünü alır veya ayarlar. |
| [setFullPath(String value)](#setFullPath-java.lang.String-) | PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın tam yolunu alır veya ayarlar. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Kaynak özelliklerini tanımlayan OSTypeStructure dizisini alır veya ayarlar. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Bu PSD bağlantı veri kaynağının Adobe® Photoshop® \u0421\u0421 Kütüphane öğesine bağlanıp bağlanmadığını gösteren bir değeri alır. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Alt belge için şu anda seçili olan Comp'in özgün kimliğini alır; hiçbiri seçilmemişse -1 olur. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Adobe® Photoshop® global bağlantı kaynağındaki veri kaynağının özgün dosya adını alır. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Özellik değerini tip yapısına göre ayarlar. |
| [setRelativePath(String value)](#setRelativePath-java.lang.String-) | PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın göreli yolunu alır veya ayarlar. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | PSD bağlantı kaynağındaki veri kaynağının küresel benzersiz tanımlayıcısını alır. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Öğeler OSTypeStructures özelliklerinden önce gelen bilinmeyen veriyi alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFeDataSource() {#LiFeDataSource--}
```
public LiFeDataSource()
```


Yeni bir [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) sınıf örneği başlatır.

### LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


Yeni bir [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) sınıf örneği başlatır.

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

### create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFeDataSource create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| version | int |  |
| uniqueId | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource)
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
### getAdobeStockId() {#getAdobeStockId--}
```
public final String getAdobeStockId()
```


Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi AdobeStockId değerini alır veya ayarlar.

**Returns:**
java.lang.String
### getAdobeStockLicenseState() {#getAdobeStockLicenseState--}
```
public final String getAdobeStockLicenseState()
```


Adobe® Photoshop® CC kütüphaneleri için mevcutsa Adobe stok lisansının durumunu alır.

Değer: adobe stock lisansının durumu veya mevcut değilse boş dize.

**Returns:**
java.lang.String
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
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Ek verinin uzunluğunu alır.

Değer: Verinin uzunluğu.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Bağlantı kaynak verisinin uzunluğunu alır.

**Returns:**
long - Kaynak veri uzunluğu.
### getDate() {#getDate--}
```
public final Date getDate()
```


PSD LnkE kaynağının LiFE veri kaynağındaki dış dosyanın son yazma tarih ve saatini alır veya ayarlar.

**Returns:**
java.util.Date
### getDate_internalized() {#getDate-internalized--}
```
public final System.DateTime getDate_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getElementName() {#getElementName--}
```
public final String getElementName()
```


Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi öğesi adını alır veya ayarlar.

**Returns:**
java.lang.String
### getElementRef() {#getElementRef--}
```
public final String getElementRef()
```


Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi öğesi referansını alır veya ayarlar.

**Returns:**
java.lang.String
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


PSD formatındaki LnkE / Lnk2 kaynağında dosya oluşturucusunu alır veya ayarlar.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


PSD bağlantı kaynağındaki harici veya gömülü dosyanın adını alır veya ayarlar.

Değer: Dış veya gömülü dosyanın adı.

**Returns:**
java.lang.String
### getFileSize() {#getFileSize--}
```
public final long getFileSize()
```


PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın boyutunu alır veya ayarlar.

**Returns:**
long
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağlandığı gömülü veya harici dosyanın türünü alır veya ayarlar.

**Returns:**
java.lang.String
### getFullPath() {#getFullPath--}
```
public final String getFullPath()
```


PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın tam yolunu alır veya ayarlar.

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
### getRelativePath() {#getRelativePath--}
```
public final String getRelativePath()
```


PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın göreli yolunu alır veya ayarlar.

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

### setAdobeStockId(String value) {#setAdobeStockId-java.lang.String-}
```
public final void setAdobeStockId(String value)
```


Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi AdobeStockId değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


PSD LnkE kaynağının LiFE veri kaynağındaki dış dosyanın son yazma tarih ve saatini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### setDate_internalized(System.DateTime value) {#setDate-internalized-com.aspose.ms.System.DateTime-}
```
public final void setDate_internalized(System.DateTime value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.ms.System.DateTime |  |

### setElementName(String value) {#setElementName-java.lang.String-}
```
public final void setElementName(String value)
```


Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi öğesi adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setElementRef(String value) {#setElementRef-java.lang.String-}
```
public final void setElementRef(String value)
```


Adobe® Photoshop® CC Kütüphaneleri için grafik kütüphanesi öğesi referansını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


PSD formatındaki LnkE / Lnk2 kaynağında dosya oluşturucusunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


PSD bağlantı kaynağındaki harici veya gömülü dosyanın adını alır veya ayarlar.

Değer: Dış veya gömülü dosyanın adı.

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

### setFileSize(long value) {#setFileSize-long-}
```
public final void setFileSize(long value)
```


PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın boyutunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağlandığı gömülü veya harici dosyanın türünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFullPath(String value) {#setFullPath-java.lang.String-}
```
public final void setFullPath(String value)
```


PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın tam yolunu alır veya ayarlar.

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

### setRelativePath(String value) {#setRelativePath-java.lang.String-}
```
public final void setRelativePath(String value)
```


PSD LnkE kaynağının LiFE veri kaynağındaki harici dosyanın göreli yolunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

