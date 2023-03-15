---
title: GradientOverlayEffect.EffectType
second_title: Aspose.PSD voor .NET API-referentie
description: GradientOverlayEffect eigendom. Krijgt een type effect
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/effecttype/
---
## GradientOverlayEffect.EffectType property

Krijgt een type effect

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Voorbeelden

De volgende code demonstreert de ondersteuning van de eigenschap ILayerEffect.EffectType.

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
            // het ving
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Zie ook

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [GradientOverlayEffect](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../gradientoverlayeffect/)
* montage [Aspose.PSD](../../../)


