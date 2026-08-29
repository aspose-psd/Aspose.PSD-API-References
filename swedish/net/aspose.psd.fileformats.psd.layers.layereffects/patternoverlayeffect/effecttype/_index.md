---
title: "PatternOverlayEffect.EffectType"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PatternOverlayEffect egenskap. Hämtar en effekttyp"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/effecttype/
---
{{< psd/tize >}}
## PatternOverlayEffect.EffectType property

Hämtar en typ av effekt.

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
* class [PatternOverlayEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


