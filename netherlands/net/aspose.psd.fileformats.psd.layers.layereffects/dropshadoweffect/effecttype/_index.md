---
title: DropShadowEffect.EffectType
second_title: Aspose.PSD voor .NET API-referentie
description: DropShadowEffect eigendom. Krijgt een type effect
type: docs
weight: 50
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/
---
## DropShadowEffect.EffectType property

Krijgt een type effect

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Voorbeelden

De volgende code demonstreert het gebruik van de eigenschap Opacity van DropShadowEffect.

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

    // Voorbeeld met dekking = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Voorbeeld met dekking = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

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
* class [DropShadowEffect](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* montage [Aspose.PSD](../../../)


