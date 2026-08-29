---
title: "StrokeEffect.EffectType"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "StrokeEffect-Eigenschaft. Ruft einen Effekttyp ab"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/effecttype/
---
{{< psd/tize >}}
## StrokeEffect.EffectType property

Liest einen Effekttyp

```csharp
public LayerEffectsTypes EffectType { get; }
```

## Beispiele

Der folgende Code demonstriert die Unterstützung der ILayerEffect.EffectType‑Eigenschaft.

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
            // es wurde abgefangen
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Siehe auch

* enum [LayerEffectsTypes](../../layereffectstypes/)
* class [StrokeEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


