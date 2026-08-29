---
title: "DropShadowEffect.EffectType"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "DropShadowEffect-Eigenschaft. Liest den Typ des Effekts"
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/
---
{{< psd/tize >}}
## DropShadowEffect.EffectType property

Liest einen Effekttyp

```csharp
public LayerEffectsTypes EffectType { get; }
```

## Beispiele

Der folgende Code demonstriert die Verwendung der Opacity-Eigenschaft von DropShadowEffect.

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

    // Beispiel mit Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Beispiel mit Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

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
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


