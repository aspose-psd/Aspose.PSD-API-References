---
title: Class LiFdDataSource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LiFdDataSource sınıf. Katıştırılmış bir dosya hakkında bilgi içeren PSD Dosyasında liFD veri kaynağı sınıfını tanımlar. Bu Adobe Photoshop dosyalarını değiştirmeye yardımcı olan PSD Dosya Biçimi Manipülasyon APIsinin bir parçasıdır
type: docs
weight: 2670
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---
## LiFdDataSource class

Katıştırılmış bir dosya hakkında bilgi içeren PSD Dosyasında liFD veri kaynağı sınıfını tanımlar. Bu, Adobe® Photoshop® dosyalarını değiştirmeye yardımcı olan PSD Dosya Biçimi Manipülasyon API'sinin bir parçasıdır

```csharp
public class LiFdDataSource : LinkDataSource
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LiFdDataSource](lifddatasource/#constructor)() | Yeni bir örneğini başlatır.`LiFdDataSource` sınıf. |
| [LiFdDataSource](lifddatasource/#constructor_1)(int, Guid, string, string, string) | Yeni bir örneğini başlatır.`LiFdDataSource` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | PSD varlığının kilitli olup olmadığını gösteren bir değer alır veya ayarlar. Adobe® Photoshop® СС Kitaplıkları varlıkları için varlık kilitli durumu. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Adobe® Photoshop® СС Kitaplıkları varlıkları için varlığın değiştirilme süresini alır veya ayarlar. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Lnk2 / LnkE Adobe® Photoshop® kaynağının liFE veya liFD veri kaynağındaki alt belge tanımlayıcısını alır veya ayarlar. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Alt belge için seçili olan kompozisyonun kimliğini alır veya ayarlar; hiçbiri seçilmezse -1 olur. Kompozisyonlar, tasarımcıların oluşturabileceği bir sayfa düzeninin kompozisyonlarıdır. Katman kompozisyonlarını kullanarak, tek bir Adobe® Photoshop® dosyasında bir mizanpajın birden çok sürümünü oluşturabilir, yönetebilir ve görüntüleyebilirsiniz. Katman kompozisyonu, Katmanlar panelinin bir durumunun anlık görüntüsüdür. Katman kompozisyonları, üç tip katman seçeneğini kaydeder but bu özellik, Akıllı Nesneler için Katman Kompozisyonu seçim tanımlayıcısını alır. [Akıllı Nesnelerde katman kompozisyonları](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Data](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) { get; set; } | PSD dosyasındaki katıştırılmış akıllı nesne verilerini alır veya ayarlar. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | PSD formatındaki dosya oluşturucuyu alır veya ayarlar LnkE / Lnk2 kaynağı. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağladığı gömülü veya harici dosyanın türünü alır veya ayarlar. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Bu bağlantı veri kaynağının dosya açık tanımlayıcısına sahip olup olmadığını gösteren bir değer alır veya ayarlar: CompId ve OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Bu PSD bağlantı veri kaynağının Adobe® Photoshop® СС Kitaplığı öğesine bağlanıp bağlanmadığını gösteren bir değer alır. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Bayt cinsinden bağlantı veri kaynağı uzunluğunu alır. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Alt belge için geçerli olarak seçili Comp'un orijinal kimliğini alır; hiçbiri seçilmezse -1 olur. Bu özellik, Akıllı Nesneler için orijinal katman Comp seçim tanımlayıcısını alır. [Akıllı Nesnelerde katman kompozisyonları](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Adobe® Photoshop® global bağlantı kaynağındaki veri kaynağının orijinal dosya adını alır. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Aşağıdakilerden biri veya hiçbiri olabilen Adobe® Photoshop® global bağlantı veri kaynağı türünü alır: PSD'ye karşılık gelen katıştırılmış bağlantılı dosya liFD Lnk2Resource PSD'ye karşılık gelen harici bağlantılı dosya liFE LnkeResource Bağlantılı dosya takma adı liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | PSD bağlantı kaynağındaki veri kaynağının genel benzersiz tanımlayıcısını alır. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | PSD LnkE / Lnk2 kaynağındaki veri kaynağının sürümünü alır. |

### Ayrıca bakınız

* class [LinkDataSource](../linkdatasource/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* toplantı [Aspose.PSD](../../)


