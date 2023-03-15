---
title: PatternOverlayEffect.EffectType
second_title: Aspose.PSD for .NET API Referansı
description: PatternOverlayEffect mülk. Bir tür efekt alır type
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/effecttype/
---
## PatternOverlayEffect.EffectType property

Bir tür efekt alır type

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Örnekler

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

### Ayrıca bakınız

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [PatternOverlayEffect](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../patternoverlayeffect/)
* toplantı [Aspose.PSD](../../../)


