---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD for .NET API Referansı
description: Ad alanı PSD dosya formatı katmanlarını içerir.
type: docs
weight: 210
url: /tr/net/aspose.psd.fileformats.psd.layers/
---
Ad alanı, PSD dosya formatı katmanlarını içerir.

## sınıflar

| Sınıf | Tanım |
| --- | --- |
| [BlendRange](./blendrange/) | Karışım aralığı. |
| [ChannelInformation](./channelinformation/) | Kanal bilgisi. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Genel katman maskesi bölümü. |
| [Layer](./layer/) | psd katmanı. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Katman karıştırma aralıkları verileri. |
| [LayerGroup](./layergroup/) | Grup katmanı class |
| [LayerHashCalculator](./layerhashcalculator/) | PSD Katmanları için Hash Hesaplayıcı. Farklı PSD dosyalarında eşit veya farklı katmanlar bulmak için kullanılabilir |
| [LayerMaskData](./layermaskdata/) | PSD dosyasındaki katman maskesi verileri hakkında bilgi içeren temel LayerMaskData sınıfını tanımlar. Adobe® Photoshop® dosyalarını programlı olarak değiştirmeye ve PSD biçimi düzenlemeyi otomatikleştirmeye yardımcı olabilir. Katmanın yalnızca tarama maskesi varsa, ImageData taramayı içerir maske veri baytları. Katmanın yalnızca bir vektör maskesi varsa, ImageData vektör maskesi rasterleştirilmiş (önbelleğe alınmış) veri baytlarını içerir. bu[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)bayt uzunluğu Genişlik * Yükseklik eşit olmalıdır[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) property. Kanalların güncellenmemesi nedeniyle, yalnızca LayerMaskData'yı kaldırmanın / eklemenin / güncellemenin doğru save için yeterli olmadığına dikkat edin; ancak doğru oluşturmayı sağlayabilir. [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) Bunun için yöntem kullanılmalıdır. |
| [LayerMaskDataFull](./layermaskdatafull/) | Katman hem katman hem de vektör maskelerine sahip olduğunda, Layer PSD dosyasındaki maske verileri hakkında bilgi içeren LayerMaskDataFull sınıfını tanımlar. Aksi takdirde, bir[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) kullanılır. ImageData, tarama maskesini ve birleştirilmiş rasterleştirilmiş vektör maskesini içerir. ImageData bayt uzunluğu, MaskRectangle.Width * MaskRectangle.Height özellikleri. 'ye eşit olmalıdır. |
| [LayerMaskDataShort](./layermaskdatashort/) | Katman yalnızca raster veya vektör maskesine sahipken, her ikisine birden sahip olmadığında, Layer PSD dosyasındaki maske verileri hakkında bilgi içeren LayerMaskDataShort sınıfını tanımlar. Aksi takdirde, bir[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) kullanılır. Katmanın yalnızca bir tarama maskesi varsa, ImageData, tarama maskesi veri baytlarını içerir. Katmanın yalnızca bir vektör maskesi varsa, ImageData, rasterleştirilmiş (önbelleğe alınmış) veri baytlarını içeren vektör maskesini içerir.[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)bayt uzunluğu Genişlik * Yükseklik eşit olmalıdır[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) özellikler. |
| [LayerResource](./layerresource/) | Katman bilgisini temsil eder. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Yüklenen PSD dosyaları için katman kaynakları kaydını tanımlayın. |
| [LinkedLayersManager](./linkedlayersmanager/) | Bağlantılı katmanlar yöneticisi sınıfı. |
| [SectionDividerLayer](./sectiondividerlayer/) | Klasörün (katman grubu) sınırlarını işaretlemek için bölüm ayırıcı katman. |
| [TextLayer](./textlayer/) | Metin katmanı class |
## Arayüzler

| Arayüz | Tanım |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Dolgu ayarları için temel arayüz |
| [ILayerResourceLoader](./ilayerresourceloader/) | Katman kaynak yükleyicisi. |
## numaralandırma

| numaralandırma | Tanım |
| --- | --- |
| [LayerFlags](./layerflags/) | Katman flags |
| [LayerMaskFlags](./layermaskflags/) | Katman maskesi flags |


