---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Aspose.PSD for .NET API Referansı
description: PsdImage yöntem. Titreşim ayarlama katmanını ekler.
type: docs
weight: 430
url: /tr/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

Titreşim ayarlama katmanını ekler.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Geri dönüş değeri

Yeni oluşturulmuş bir Titreşim katmanı.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)


