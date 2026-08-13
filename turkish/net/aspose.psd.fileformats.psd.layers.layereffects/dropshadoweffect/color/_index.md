---
title: "DropShadowEffect.Color"
second_title: "Aspose.PSD for .NET API Referansı"
description: "DropShadowEffect özelliği. Rengi alır veya ayarlar"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/
---
{{< psd/tize >}}
## DropShadowEffect.Color property

Rengi alır veya ayarlar.

```csharp
public Color Color { get; set; }
```

### Property Value

Renk.

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

* struct [Color](../../../aspose.psd/color/)
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


