---
title: OuterGlowEffect.BlendMode
second_title: Aspose.PSD per riferimento API .NET
description: OuterGlowEffect proprietà. Ottiene o imposta la modalità di fusione.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
## OuterGlowEffect.BlendMode property

Ottiene o imposta la modalità di fusione.

```csharp
public BlendMode BlendMode { get; set; }
```

### Valore della proprietà

La modalità di fusione.

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* assemblea [Aspose.PSD](../../../)


