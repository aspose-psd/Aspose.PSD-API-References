---
title: "VibranceLayer.Vibrance"
second_title: "Aspose.PSD for .NET API Referansı"
description: "VibranceLayer özelliği. Canlılığı alır veya ayarlar"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

Vibrance'ı alır veya ayarlar.

```csharp
public int Vibrance { get; set; }
```

### Property Value

Canlılık.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | Canlılık -180 ile +180 arasında olmalıdır |

## Örnekler

Aşağıdaki kod örneği, VibranceLayer katmanının desteğini ve bu ayarın düzenlenebilme yeteneğini gösterir.

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

### Ayrıca Bakınız

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


