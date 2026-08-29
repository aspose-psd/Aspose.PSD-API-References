---
title: "InnerShadowEffect.EffectType"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "InnerShadowEffect ιδιότητα. Λαμβάνει έναν τύπο εφέ"
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/
---
{{< psd/tize >}}
## InnerShadowEffect.EffectType property

Λαμβάνει έναν τύπο εφέ

```csharp
public LayerEffectsTypes EffectType { get; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της ιδιότητας ILayerEffect.EffectType.

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
            // το συνέλαβε
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Δείτε επίσης

* enum [LayerEffectsTypes](../../layereffectstypes/)
* class [InnerShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


