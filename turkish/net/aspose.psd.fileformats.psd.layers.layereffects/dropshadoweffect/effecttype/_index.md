---
title: "DropShadowEffect.EffectType"
second_title: "Aspose.PSD for .NET API Referansı"
description: "DropShadowEffect özelliği. Bir etki türünü alır"
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/
---
{{< psd/tize >}}
## DropShadowEffect.EffectType property

Bir efekt türünü alır.

```csharp
public LayerEffectsTypes EffectType { get; }
```

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

Aşağıdaki kod, ILayerEffect.EffectType özelliğinin desteğini gösterir.

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // yakalandı
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Ayrıca Bakınız

* enum [LayerEffectsTypes](../../layereffectstypes/)
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


