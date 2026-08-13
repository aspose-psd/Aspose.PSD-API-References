---
title: "DropShadowEffect.Angle"
second_title: "Aspose.PSD for .NET API Referansı"
description: "DropShadowEffect özelliği. Açıyı derece cinsinden alır veya ayarlar"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
{{< psd/tize >}}
## DropShadowEffect.Angle property

Açıyı derece cinsinden alır veya ayarlar.

```csharp
public int Angle { get; set; }
```

### Property Value

Açı.

## Örnekler

Aşağıdaki kod, DropShadowEffect'in Opacity özelliğinin kullanımını gösterir.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Opacity = 20 ile örnek
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Opacity = 200 ile örnek
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Ayrıca Bakınız

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


