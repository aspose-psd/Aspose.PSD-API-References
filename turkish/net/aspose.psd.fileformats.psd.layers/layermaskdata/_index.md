---
title: "Sınıf LayerMaskData"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData sınıfı. PSD dosyasındaki katman maskesi verileri hakkında bilgi içeren temel LayerMaskData sınıfını tanımlar. Adobe Photoshop dosyalarını programlı olarak değiştirmeye ve PSD formatı düzenlemesini otomatikleştirmeye yardımcı olabilir. Katmanın yalnızca bir raster maskesi varsa ImageData raster maske veri baytlarını içerir. Katmanın yalnızca bir vektör maskesi varsa ImageData vektör maskesinin rasterleştirilmiş önbellek veri baytlarını içerir. Katmanın hem katman hem de vektör maskeleri varsa ImageData raster maskeyi ve rasterleştirilmiş vektör maskesini birleştirir. ImageData bayt uzunluğu MaskRectangle özelliklerinin Width ve Height değerlerine eşit olmalıdır. Sadece LayerMaskData'yı kaldırmanın/eklemenin/güncellemenin doğru kaydetme için yeterli olmadığını, çünkü kanallar güncellenmez, ancak doğru render alabilir. Bunun için AddLayerMask yöntemi kullanılmalıdır."
type: docs
weight: 2440
url: /tr/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

Temel LayerMaskData sınıfını tanımlar; bu sınıf PSD dosyasındaki katman maskesi verileri hakkında bilgi içerir. Adobe® Photoshop® dosyalarını programlı olarak değiştirmeye ve PSD formatı düzenlemesini otomatikleştirmeye yardımcı olabilir. Katmanın yalnızca bir raster maskesi varsa ImageData raster maske veri baytlarını içerir. Katmanın yalnızca bir vektör maskesi varsa ImageData vektör maskesinin rasterleştirilmiş (önbelleklenmiş) veri baytlarını içerir. Katmanın hem katman hem de vektör maskeleri varsa ImageData raster maskeyi ve rasterleştirilmiş vektör maskesini birleştirir. [`ImageData`](./imagedata/) bayt uzunluğu, [`MaskRectangle`](./maskrectangle/) özelliklerinin Width * Height değerine eşit olmalıdır. Sadece LayerMaskData'yı kaldırmanın/eklemenin/güncellemenin doğru kaydetme için yeterli olmadığını, çünkü kanallar güncellenmez; ancak doğru render alabilir. Bunun için [`AddLayerMask`](../layer/addlayermask/) yöntemi kullanılmalıdır.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Sağ katman maskesi konumunu alır veya ayarlar. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Üst katman maskesi konumunu alır veya ayarlar. |

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


