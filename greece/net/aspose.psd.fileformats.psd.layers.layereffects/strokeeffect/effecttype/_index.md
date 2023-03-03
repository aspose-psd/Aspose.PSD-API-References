---
title: StrokeEffect.EffectType
second_title: Aspose.PSD για Αναφορά API .NET
description: StrokeEffect ιδιοκτησία. Λαμβάνει έναν τύπο εφέ
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/effecttype/
---
## StrokeEffect.EffectType property

Λαμβάνει έναν τύπο εφέ

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει την υποστήριξη της ιδιότητας ILayerEffect.EffectType.

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
            // έπιασε
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Δείτε επίσης

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [StrokeEffect](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* συνέλευση [Aspose.PSD](../../../)


