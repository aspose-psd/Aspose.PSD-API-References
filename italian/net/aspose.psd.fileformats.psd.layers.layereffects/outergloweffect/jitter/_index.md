---
title: OuterGlowEffect.Jitter
second_title: Aspose.PSD per riferimento API .NET
description: OuterGlowEffect proprietà. Ottiene o imposta il rumore.
type: docs
weight: 80
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/
---
## OuterGlowEffect.Jitter property

Ottiene o imposta il rumore.

```csharp
public int Jitter { get; set; }
```

### Valore della proprietà

Il rumore.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Il rumore deve essere specificato come percentuale nell'intervallo da 0 a 100 |

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


