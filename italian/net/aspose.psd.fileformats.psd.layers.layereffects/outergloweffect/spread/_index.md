---
title: OuterGlowEffect.Spread
second_title: Aspose.PSD per riferimento API .NET
description: OuterGlowEffect proprietà. Ottiene o imposta lintensità come percentuale.
type: docs
weight: 130
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/
---
## OuterGlowEffect.Spread property

Ottiene o imposta l'intensità come percentuale.

```csharp
public int Spread { get; set; }
```

### Valore della proprietà

Lo spread.

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


