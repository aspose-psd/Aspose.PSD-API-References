---
title: Class LayerMaskDataFull
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull sınıf. Katman hem katman hem de vektör maskelerine sahip olduğunda Layer PSD dosyasındaki maske verileri hakkında bilgi içeren LayerMaskDataFull sınıfını tanımlar. Aksi takdirde birLayerMaskDataShort kullanılır. ImageData tarama maskesini ve birleştirilmiş rasterleştirilmiş vektör maskesini içerir. ImageData bayt uzunluğu MaskRectangle.Width  MaskRectangle.Height özellikleri. ye eşit olmalıdır.
type: docs
weight: 2250
url: /tr/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

Katman hem katman hem de vektör maskelerine sahip olduğunda, Layer PSD dosyasındaki maske verileri hakkında bilgi içeren LayerMaskDataFull sınıfını tanımlar. Aksi takdirde, bir[`LayerMaskDataShort`](../layermaskdatashort/) kullanılır. ImageData, tarama maskesini ve birleştirilmiş rasterleştirilmiş vektör maskesini içerir. ImageData bayt uzunluğu, MaskRectangle.Width * MaskRectangle.Height özellikleri. 'ye eşit olmalıdır.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Arka plan rengini alır veya ayarlar. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Alt katman maskesi konumunu alır veya ayarlar. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Katman maskesi maske verilerinin boyutunu alır. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Varsayılan rengi alır veya ayarlar. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | PSD görüntü katmanındaki çevreleyen alt raster maske konumunu alır veya ayarlar. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | PSD dosya katmanındaki çevreleyen sol raster maske konumunu alır veya ayarlar. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | PSD dosya katmanındaki çevreleyen sağ raster maske konumunu alır veya ayarlar. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | PSD görüntü katmanında tarama maskesinin çevreleyen üst konumunu alır veya ayarlar. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Katman maskesi bayraklarını alır veya ayarlar. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD dosyasındaki katman maskesi verilerini (veya bir vektör maskesi varsa birleştirilmiş / son maskeyi) alır veya ayarlar. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Sol katman maskesi konumunu alır veya ayarlar. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Maskeyi alır veya ayarlar[`Rectangle`](../../aspose.psd/rectangle/)PSD dosyasındaki katman maskesinin. Left, right, top ve bottom özelliklerini alır ve oluşturur[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Kullanıcı / tarama maskesi için kullanılan katman maskesi bayraklarını alır veya ayarlar. Vektör maskesi için Bayraklar özelliği kullanılır. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Doğru katman maskesi konumunu alır veya ayarlar. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Üst katman maskesi konumunu alır veya ayarlar. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | PSD dosyasındaki bir katmanın kullanıcı (raster) maske verilerini alır veya ayarlar. (MaskData özelliğinde derecelendirilmiş bir vektör maskesi vardır). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | PSD görüntü katmanında kullanıcı maskesi (çevreleyen) dikdörtgeni alır veya ayarlar.. |

### Ayrıca bakınız

* class [LayerMaskData](../layermaskdata/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* toplantı [Aspose.PSD](../../)


