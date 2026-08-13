---
title: "Sınıf LinkDataSource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource sınıfı. PSD dosyasındaki bağlı bir dosya veya varlık hakkında bilgi içeren LinkDataSource sınıfını tanımlar."
type: docs
weight: 2990
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
{{< psd/tize >}}
## LinkDataSource class

PSD dosyasındaki bir bağlantılı dosya veya varlık hakkında bilgi içeren LinkDataSource sınıfını tanımlar.

```csharp
public abstract class LinkDataSource
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | PSD varlığının kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. Adobe® Photoshop® СС Libraries varlıkları için varlık kilitli durumu. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Adobe® Photoshop® СС Libraries varlıkları için varlık değiştirilme zamanını alır veya ayarlar. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Lnk2 / LnkE Adobe® Photoshop® kaynağının liFE veya liFD veri kaynağındaki alt belge tanımlayıcısını alır veya ayarlar. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Alt belge için şu anda seçili olan comp'ın kimliğini alır veya ayarlar; hiçbiri seçilmemişse -1 olur. Comp'lar, tasarımcıların oluşturabileceği bir sayfa düzeninin kompozisyonlarıdır. Katman comp'larını kullanarak tek bir Adobe® Photoshop® dosyasında bir düzenin birden çok sürümünü oluşturabilir, yönetebilir ve görüntüleyebilirsiniz. Katman comp'ı, Katmanlar panelinin bir durumunun anlık görüntüsüdür. Katman comp'ları üç tür katman seçeneğini kaydeder ancak bu özellik, Akıllı Nesneler için Katman Comp seçim tanımlayıcısını alır. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | PSD formatı LnkE / Lnk2 kaynağındaki dosya oluşturucusunu alır veya ayarlar. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağlandığı gömülü veya harici dosyanın türünü alır veya ayarlar. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Bu bağlantı veri kaynağının dosya açık tanımlayıcısına (CompId ve OriginalCompId) sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Bu PSD bağlantı veri kaynağının Adobe® Photoshop® СС Library öğesine bağlanıp bağlanmadığını gösteren bir değeri alır. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Bağlantı veri kaynağının uzunluğunu bayt cinsinden alır. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Alt belge için şu anda seçili olan Comp'ın orijinal kimliğini alır; hiçbiri seçilmemişse -1 olur. Bu özellik, Akıllı Nesneler için orijinal katman Comp seçim tanımlayıcısını alır. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Adobe® Photoshop® global bağlantı kaynağındaki veri kaynağının orijinal dosya adını alır. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Adobe® Photoshop® global bağlantı veri kaynağı türünü alır; aşağıdakilerden biri veya hiçbiri olabilir: PSD Lnk2Resource ile eşleşen gömülü bağlı dosya liFD, PSD LnkeResource ile eşleşen harici bağlı dosya liFE, bağlı dosya takma adı liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | PSD bağlantı kaynağındaki veri kaynağının küresel benzersiz tanımlayıcısını alır. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | PSD LnkE / Lnk2 kaynağındaki veri kaynağının sürümünü alır. |

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


