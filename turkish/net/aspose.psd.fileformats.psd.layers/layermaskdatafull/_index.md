---
title: "Sınıf LayerMaskDataFull"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull sınıfı. Katmanın hem katman hem de vektör maskeleri olduğunda PSD dosyası katmanındaki maske verileri hakkında bilgi içeren LayerMaskDataFull sınıfını tanımlar. Aksi takdirde LayerMaskDataShort kullanılır. ImageData raster maskeyi ve rasterleştirilmiş vektör maskesini birleştirir. ImageData bayt uzunluğu MaskRectangle.Width * MaskRectangle.Height özelliklerine eşit olmalıdır."
type: docs
weight: 2450
url: /tr/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

Katmanın hem katman hem de vektör maskeleri olduğunda PSD dosyası katmanındaki maske verileri hakkında bilgi içeren LayerMaskDataFull sınıfını tanımlar. Aksi takdirde, bir [`LayerMaskDataShort`](../layermaskdatashort/) kullanılır. ImageData raster maskeyi ve rasterleştirilmiş vektör maskesini birleştirir. ImageData bayt uzunluğu MaskRectangle.Width * MaskRectangle.Height özelliklerine eşit olmalıdır.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Arka plan rengini alır veya ayarlar. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Alt katman maskesi konumunu alır veya ayarlar. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Katman maskesi veri boyutunu alır. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Varsayılan rengi alır veya ayarlar. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | PSD görüntü katmanındaki kapsayan alt raster maske konumunu alır veya ayarlar. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | PSD dosyası katmanındaki kapsayan sol raster maske konumunu alır veya ayarlar. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | PSD dosyası katmanındaki kapsayan sağ raster maske konumunu alır veya ayarlar. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | PSD görüntü katmanındaki kapsayan üst raster maske konumunu alır veya ayarlar. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Katman maskesi bayraklarını alır veya ayarlar. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD dosyasındaki katman maskesi verisini (veya bir vektör maskesi varsa birleştirilmiş / son maskeyi) alır veya ayarlar. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Sol katman maskesi konumunu alır veya ayarlar. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | PSD dosyasındaki katman maskesinin maskesini [`Rectangle`](../../aspose.psd/rectangle/) alır veya ayarlar. Sol, sağ, üst ve alt özelliklerini alır ve bir [`Rectangle`](../../aspose.psd/rectangle/) oluşturur. |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Kullanıcı / raster maskesi için kullanılan katman maskesi bayraklarını alır veya ayarlar. Vektör maskesi için Flags özelliği kullanılır. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Sağ katman maskesi konumunu alır veya ayarlar. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Üst katman maskesi konumunu alır veya ayarlar. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | PSD dosyasındaki bir katmanın kullanıcı (raster) maske verisini alır veya ayarlar. (MaskData özelliğinde rasterleştirilmiş bir vektör maskesi vardır). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | PSD görüntü katmanındaki kullanıcı maskesi (kapsayan) dikdörtgenini alır veya ayarlar. |

### Ayrıca Bakınız

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


