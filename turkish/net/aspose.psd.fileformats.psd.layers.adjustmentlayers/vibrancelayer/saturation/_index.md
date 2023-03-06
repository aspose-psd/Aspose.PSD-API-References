---
title: VibranceLayer.Saturation
second_title: Aspose.PSD for .NET API Referansı
description: VibranceLayer mülk. Doygunluğu alır veya ayarlar.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
## VibranceLayer.Saturation property

Doygunluğu alır veya ayarlar.

```csharp
public int Saturation { get; set; }
```

### Mülk değeri

Doygunluk.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | Doygunluk -100 ile +100 aralığında olmalıdır |

### Örnekler

Aşağıdaki kod örneği, VibranceLayer katmanının desteğini ve bu ayarı düzenleme yeteneğini gösterir.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Yeni bir VibranceLayer oluşturma
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Ayrıca bakınız

* class [VibranceLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* toplantı [Aspose.PSD](../../../)


