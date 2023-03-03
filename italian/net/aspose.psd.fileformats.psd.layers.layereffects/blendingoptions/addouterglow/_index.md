---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD per riferimento API .NET
description: BlendingOptions metodo. Aggiunge leffetto bagliore esterno.
type: docs
weight: 60
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

Aggiunge l'effetto bagliore esterno.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Valore di ritorno

Creato[`OuterGlowEffect`](../../outergloweffect/) oggetto

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* assemblea [Aspose.PSD](../../../)


