---
title: "Sınıf LayerMaskDataShort"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort sınıfı. LayerMaskDataShort sınıfını tanımlar; bu sınıf, katmanın yalnızca raster veya vektör maskesi olduğunda, ancak ikisi birden olmadığında PSD dosyası katmanındaki maske verileri hakkında bilgi içerir. Aksi takdirde LayerMaskDataFull kullanılır. Katmanın yalnızca raster maskesi varsa ImageData raster maske veri baytlarını içerir. Katmanın yalnızca vektör maskesi varsa ImageData vektör maskesinin rasterleştirilmiş önbellek veri baytlarını içerir. ImageData bayt uzunluğu, MaskRectangle özelliklerinin Genişlik * Yükseklik değerine eşit olmalıdır."
type: docs
weight: 2460
url: /tr/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

LayerMaskDataShort sınıfını tanımlar; bu sınıf, katmanın yalnızca raster veya vektör maskesi olduğunda, ancak ikisi birden olmadığında PSD dosyası katmanındaki maske verileri hakkında bilgi içerir. Aksi takdirde, bir [`LayerMaskDataFull`](../layermaskdatafull/) kullanılır. Katmanın yalnızca raster maskesi varsa ImageData raster maske veri baytlarını içerir. Katmanın yalnızca vektör maskesi varsa ImageData vektör maskesinin rasterleştirilmiş (önbelleklenmiş) veri baytlarını içerir. [`ImageData`](../layermaskdata/imagedata/) bayt uzunluğu, [`MaskRectangle`](../layermaskdata/maskrectangle/) özelliklerinin Genişlik * Yükseklik değerine eşit olmalıdır.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Yeni bir `LayerMaskDataShort` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Alt katman maskesi konumunu alır veya ayarlar. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Katman maskesi veri boyutunu alır. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Varsayılan rengi alır veya ayarlar. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Katman maskesi bayraklarını alır veya ayarlar. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD dosyasındaki katman maskesi verisini (veya bir vektör maskesi varsa birleştirilmiş / son maskeyi) alır veya ayarlar. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Sol katman maskesi konumunu alır veya ayarlar. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | PSD dosyasındaki katman maskesinin maskesini [`Rectangle`](../../aspose.psd/rectangle/) alır veya ayarlar. Sol, sağ, üst ve alt özelliklerini alır ve bir [`Rectangle`](../../aspose.psd/rectangle/) oluşturur. |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Katman maskesi dolgusunu alır veya ayarlar. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Sağ katman maskesi konumunu alır veya ayarlar. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Üst katman maskesi konumunu alır veya ayarlar. |

### Ayrıca Bakınız

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


