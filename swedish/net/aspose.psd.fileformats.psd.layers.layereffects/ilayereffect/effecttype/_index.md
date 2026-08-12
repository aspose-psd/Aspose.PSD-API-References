---
title: "ILayerEffect.EffectType"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ILayerEffect egenskap. Hämtar en typ av effekt"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/effecttype/
---
{{< psd/tize >}}
## ILayerEffect.EffectType property

Hämtar en effekttyp

```csharp
public LayerEffectsTypes EffectType { get; }
```

## Exempel

Följande kod visar stöd för egenskapen ILayerEffect.EffectType.

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
            // det fångades
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Se även

* enum [LayerEffectsTypes](../../layereffectstypes/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


