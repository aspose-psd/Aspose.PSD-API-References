---
title: "ILayerEffect.EffectType"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ILayerEffect property. Bir efekt türünü alır"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/effecttype/
---
{{< psd/tize >}}
## ILayerEffect.EffectType property

Bir efekt türünü alır.

```csharp
public LayerEffectsTypes EffectType { get; }
```

## Örnekler

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
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


