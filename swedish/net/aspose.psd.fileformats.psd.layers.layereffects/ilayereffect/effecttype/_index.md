---
title: ILayerEffect.EffectType
second_title: Aspose.PSD för .NET API-referens
description: ILayerEffect fast egendom. Får en typ av effekt
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/effecttype/
---
## ILayerEffect.EffectType property

Får en typ av effekt

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Exempel

Följande kod visar stöd för ILayerEffect.EffectType-egenskapen.

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
            // det fångade
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Se även

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* interface [ILayerEffect](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../ilayereffect/)
* hopsättning [Aspose.PSD](../../../)


