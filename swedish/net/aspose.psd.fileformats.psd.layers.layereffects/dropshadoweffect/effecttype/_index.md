---
title: DropShadowEffect.EffectType
second_title: Aspose.PSD för .NET API-referens
description: DropShadowEffect fast egendom. Får en typ av effekt
type: docs
weight: 50
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/
---
## DropShadowEffect.EffectType property

Får en typ av effekt

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Exempel

Följande kod visar hur Opacity-egenskapen för DropShadowEffect används.

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

    // Exempel med Opacitet = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Exempel med Opacitet = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

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
* class [DropShadowEffect](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* hopsättning [Aspose.PSD](../../../)


