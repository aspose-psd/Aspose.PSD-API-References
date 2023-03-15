---
title: Class LayerMaskDataShort
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort sınıf. Katman yalnızca raster veya vektör maskesine sahipken her ikisine birden sahip olmadığında Layer PSD dosyasındaki maske verileri hakkında bilgi içeren LayerMaskDataShort sınıfını tanımlar. Aksi takdirde birLayerMaskDataFull kullanılır. Katmanın yalnızca bir tarama maskesi varsa ImageData tarama maskesi veri baytlarını içerir. Katmanın yalnızca bir vektör maskesi varsa ImageData rasterleştirilmiş önbelleğe alınmış veri baytlarını içeren vektör maskesini içerir.ImageDatabayt uzunluğu Genişlik  Yükseklik eşit olmalıdırMaskRectangle özellikler.
type: docs
weight: 2260
url: /tr/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Katman yalnızca raster veya vektör maskesine sahipken, her ikisine birden sahip olmadığında, Layer PSD dosyasındaki maske verileri hakkında bilgi içeren LayerMaskDataShort sınıfını tanımlar. Aksi takdirde, bir[`LayerMaskDataFull`](../layermaskdatafull/) kullanılır. Katmanın yalnızca bir tarama maskesi varsa, ImageData, tarama maskesi veri baytlarını içerir. Katmanın yalnızca bir vektör maskesi varsa, ImageData, rasterleştirilmiş (önbelleğe alınmış) veri baytlarını içeren vektör maskesini içerir.[`ImageData`](../layermaskdata/imagedata/)bayt uzunluğu Genişlik * Yükseklik eşit olmalıdır[`MaskRectangle`](../layermaskdata/maskrectangle/) özellikler.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Default_Constructor |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Katman maskesi dolgusunu alır veya ayarlar. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Doğru katman maskesi konumunu alır veya ayarlar. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Üst katman maskesi konumunu alır veya ayarlar. |

### Ayrıca bakınız

* class [LayerMaskData](../layermaskdata/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* toplantı [Aspose.PSD](../../)


