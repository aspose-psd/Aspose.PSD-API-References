---
title: OuterGlowEffect.FillColor
second_title: Aspose.PSD per riferimento API .NET
description: OuterGlowEffect proprietà. Ottiene o imposta il colore.
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/
---
## OuterGlowEffect.FillColor property

Ottiene o imposta il colore.

```csharp
public IFillSettings FillColor { get; set; }
```

### Valore della proprietà

Il colore.

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

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [OuterGlowEffect](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* assemblea [Aspose.PSD](../../../)


