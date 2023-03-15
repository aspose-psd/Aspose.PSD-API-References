---
title: Class LayerMaskData
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData sınıf. PSD dosyasındaki katman maskesi verileri hakkında bilgi içeren temel LayerMaskData sınıfını tanımlar. Adobe Photoshop dosyalarını programlı olarak değiştirmeye ve PSD biçimi düzenlemeyi otomatikleştirmeye yardımcı olabilir. Katmanın yalnızca tarama maskesi varsa ImageData taramayı içerir maske veri baytları. Katmanın yalnızca bir vektör maskesi varsa ImageData vektör maskesi rasterleştirilmiş önbelleğe alınmış veri baytlarını içerir. buImageDatabayt uzunluğu Genişlik  Yükseklik eşit olmalıdırMaskRectangle property. Kanalların güncellenmemesi nedeniyle yalnızca LayerMaskDatayı kaldırmanın / eklemenin / güncellemenin doğru save için yeterli olmadığına dikkat edin ancak doğru oluşturmayı sağlayabilir. AddLayerMask Bunun için yöntem kullanılmalıdır.
type: docs
weight: 2240
url: /tr/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

PSD dosyasındaki katman maskesi verileri hakkında bilgi içeren temel LayerMaskData sınıfını tanımlar. Adobe® Photoshop® dosyalarını programlı olarak değiştirmeye ve PSD biçimi düzenlemeyi otomatikleştirmeye yardımcı olabilir. Katmanın yalnızca tarama maskesi varsa, ImageData taramayı içerir maske veri baytları. Katmanın yalnızca bir vektör maskesi varsa, ImageData vektör maskesi rasterleştirilmiş (önbelleğe alınmış) veri baytlarını içerir. bu[`ImageData`](./imagedata/)bayt uzunluğu Genişlik * Yükseklik eşit olmalıdır[`MaskRectangle`](./maskrectangle/) property. Kanalların güncellenmemesi nedeniyle, yalnızca LayerMaskData'yı kaldırmanın / eklemenin / güncellemenin doğru save için yeterli olmadığına dikkat edin; ancak doğru oluşturmayı sağlayabilir. [`AddLayerMask`](../layer/addlayermask/) Bunun için yöntem kullanılmalıdır.

```csharp
public abstract class LayerMaskData
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Alt katman maskesi konumunu alır veya ayarlar. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Katman maskesi maske verilerinin boyutunu alır. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Varsayılan rengi alır veya ayarlar. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Katman maskesi bayraklarını alır veya ayarlar. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD dosyasındaki katman maskesi verilerini (veya bir vektör maskesi varsa birleştirilmiş / son maskeyi) alır veya ayarlar. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Sol katman maskesi konumunu alır veya ayarlar. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Maskeyi alır veya ayarlar[`Rectangle`](../../aspose.psd/rectangle/)PSD dosyasındaki katman maskesinin. Left, right, top ve bottom özelliklerini alır ve oluşturur[`Rectangle`](../../aspose.psd/rectangle/) |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Doğru katman maskesi konumunu alır veya ayarlar. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Üst katman maskesi konumunu alır veya ayarlar. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* toplantı [Aspose.PSD](../../)


