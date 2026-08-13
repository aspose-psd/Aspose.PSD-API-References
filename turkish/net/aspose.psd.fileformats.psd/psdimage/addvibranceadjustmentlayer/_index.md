---
title: "PsdImage.AddVibranceAdjustmentLayer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdImage yöntemi. Vibrance ayar katmanını ekler"
type: docs
weight: 490
url: /tr/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

Canlılık ayar katmanını ekler.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Dönüş Değeri

Yeni oluşturulmuş bir Vibrance katmanı.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


