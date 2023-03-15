---
title: OuterGlowEffect.Intensity
second_title: Aspose.PSD per riferimento API .NET
description: OuterGlowEffect proprietà. Ottiene o imposta langolo in gradi.
type: docs
weight: 40
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
## OuterGlowEffect.Intensity property

Ottiene o imposta l'angolo in gradi.

```csharp
public int Intensity { get; set; }
```

### Valore della proprietà

L'angolo.

### Esempi

Il codice seguente illustra il supporto OuterGlowEffect.

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### Guarda anche

* class [OuterGlowEffect](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* assemblea [Aspose.PSD](../../../)


