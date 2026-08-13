---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Ad alanı, PSD dosya formatı katmanlarını içerir"
type: docs
weight: 230
url: /tr/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
Bu ad alanı, PSD dosya formatı katmanlarını içerir.

## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | artboard katman sınıfı. |
| [BlendRange](./blendrange/) | karışım aralığı. |
| [ChannelInformation](./channelinformation/) | kanal bilgisi. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Genel katman maskesi bölümü. |
| [Layer](./layer/) | psd katmanı. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Katman karıştırma aralıkları verileri. |
| [LayerGroup](./layergroup/) | Grup katman sınıfı |
| [LayerHashCalculator](./layerhashcalculator/) | PSD Katmanları için Karma Hesaplayıcı. Farklı PSD dosyalarında eşit veya farklı katmanları bulmak için kullanılabilir. |
| [LayerMaskData](./layermaskdata/) | Temel LayerMaskData sınıfını tanımlar; bu sınıf PSD dosyasındaki katman maskesi verileri hakkında bilgi içerir. Adobe® Photoshop® dosyalarını programlı olarak değiştirmeye ve PSD formatı düzenlemesini otomatikleştirmeye yardımcı olabilir. Katmanın yalnızca raster maskesi varsa ImageData raster maske veri baytlarını içerir. Katmanın yalnızca vektör maskesi varsa ImageData vektör maskesinin rasterleştirilmiş (önbelleğe alınmış) veri baytlarını içerir. Katmanın hem katman hem de vektör maskeleri varsa ImageData raster maskeyi ve rasterleştirilmiş vektör maskesini birleştirir. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) bayt uzunluğu, [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) özelliklerinin Genişlik * Yükseklik değerine eşit olmalıdır. Dikkat, sadece LayerMaskData'yı kaldırmanın / eklemenin / güncellemenin doğru kaydetme için yeterli olmadığını; çünkü kanallar güncellenmez; yine de doğru render sağlayabilir. Bunun için [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) yöntemi kullanılmalıdır. |
| [LayerMaskDataFull](./layermaskdatafull/) | Katmanın hem katman hem de vektör maskeleri olduğunda PSD dosyası katmanındaki maske verileri hakkında bilgi içeren LayerMaskDataFull sınıfını tanımlar. Aksi takdirde, bir [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) kullanılır. ImageData raster maskeyi ve rasterleştirilmiş vektör maskesini birleştirir. ImageData bayt uzunluğu, MaskRectangle.Width * MaskRectangle.Height özelliklerine eşit olmalıdır. |
| [LayerMaskDataShort](./layermaskdatashort/) | Katmanın yalnızca raster veya vektör maskesi olduğunda (ikisi birden değil) PSD dosyası katmanındaki maske verileri hakkında bilgi içeren LayerMaskDataShort sınıfını tanımlar. Aksi takdirde, bir [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) kullanılır. Katmanın yalnızca raster maskesi varsa ImageData raster maske veri baytlarını içerir. Katmanın yalnızca vektör maskesi varsa ImageData vektör maskesinin rasterleştirilmiş (önbelleğe alınmış) veri baytlarını içerir. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) bayt uzunluğu, [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) özelliklerinin Genişlik * Yükseklik değerine eşit olmalıdır. |
| [LayerResource](./layerresource/) | Katman bilgilerini temsil eder. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | PSD dosyalarının yüklenmesi için katman kaynakları kayıt defterini tanımlayın. |
| [LinkedLayersManager](./linkedlayersmanager/) | Bağlantılı katmanlar yöneticisi sınıfı. |
| [SectionDividerLayer](./sectiondividerlayer/) | Klasörün (katman grubu) sınırlarını işaretlemek için bölüm ayırıcı katman. |
| [ShapeLayer](./shapelayer/) | Şekil katmanı. Şekil katmanı ve ilgili kaynaklarla çalışma mantığını kapsüller. |
| [TextLayer](./textlayer/) | Metin katmanı sınıfı |
## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Doldurma ayarları için temel arayüz |
| [ILayerResourceLoader](./ilayerresourceloader/) | Katman kaynak yükleyicisi. |
| [IShapeLayer](./ishapelayer/) | Şekil katmanının özelliklerini açıklar. |
## Sıralama

| Sıralama | Açıklama |
| --- | --- |
| [LayerFlags](./layerflags/) | Katman bayrakları |
| [LayerMaskFlags](./layermaskflags/) | Katman maskesi bayrakları |


