---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /tr/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Sınıf** | **Açıklama** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | artboard katman sınıfı. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | karışım aralığı. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | kanal bilgisi. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | global katman maskesi bölümü. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | Doldurma ayarları için temel arayüz |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | Katman kaynak yükleyicisi. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Shape katmanının özelliklerini açıklar. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | psd katmanı. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | Katman karıştırma aralıkları verisi. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Grup katman sınıfı |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | PSD Katmanları için Karma Hesaplayıcı. Farklı PSD dosyalarında eşit veya farklı katmanları bulmak için kullanılabilir. |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | PSD dosyasındaki katman maskesi verileri hakkında bilgi içeren temel LayerMaskData sınıfını tanımlar.<br/>            Adobe® Photoshop® dosyalarını programlı olarak değiştirmeye ve PSD formatı düzenlemesini otomatikleştirmeye yardımcı olabilir.<br/>            Katmanın yalnızca raster maskesi varsa ImageData raster maske veri baytlarını içerir.<br/>            Katmanın yalnızca vektör maskesi varsa ImageData vektör maskesinin rasterleştirilmiş (önbelleğe alınmış) veri baytlarını içerir.<br/>            Katmanın hem katman maskesi hem de vektör maskesi varsa ImageData raster maskesini ve rasterleştirilmiş vektör maskesini birleştirerek içerir.<br/>            Bu [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bayt uzunluğu, [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) özelliklerinin Width * Height değerine eşit olmalıdır.<br/>            Dikkat, sadece LayerMaskData'yı kaldırmak / eklemek / güncellemek doğru kaydetme için yeterli değildir çünkü kanallar güncellenmez; yine de doğru render sağlayabilir.<br/>            Bu işlem için [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) yöntemi kullanılmalıdır. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | LayerMaskDataFull sınıfını tanımlar ve PSD dosyası katmanındaki maske verileri hakkında bilgi içerir<br/>            katmanın hem katman hem de vektör maskeleri olduğunda. Aksi takdirde, bir [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) kullanılır.<br/>            ImageData raster maskesini ve rasterleştirilmiş vektör maskesini birleştirerek içerir.<br/>            ImageData bayt uzunluğu, MaskRectangle.Width * MaskRectangle.Height özelliklerine eşit olmalıdır. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | LayerMaskDataShort sınıfını tanımlar ve PSD dosyası katmanındaki maske verileri hakkında bilgi içerir<br/>            katmanın yalnızca raster veya vektör maskesi olduğunda, ikisi birlikte olmadığında. Aksi takdirde, bir [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) kullanılır.<br/>            Katmanın yalnızca raster maskesi varsa ImageData raster maske veri baytlarını içerir.<br/>            Katmanın yalnızca vektör maskesi varsa ImageData vektör maskesinin rasterleştirilmiş (önbelleğe alınmış) veri baytlarını içerir.<br/>            Bu [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bayt uzunluğu, [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) özelliklerinin Width * Height değerine eşit olmalıdır. |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | Katman bilgilerini temsil eder. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | PSD dosyalarının yüklenmesi için katman kaynakları kaydını tanımlar. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | Bağlantılı katmanlar yöneticisi sınıfı. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | Klasörün (katman grubu) sınırlarını işaretlemek için bölüm ayırıcı katman. |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Shape katmanı. Shape katmanı ve ilgili kaynaklarla çalışma mantığını kapsüller. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Metin katmanı sınıfı |
## **Enumerations**
| **Sınıflandırma** | **Açıklama** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | Katman bayrakları |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | Katman maskesi bayrakları |
