---
title: OuterGlowEffect.Noise
second_title: Aspose.PSD voor .NET API-referentie
description: OuterGlowEffect eigendom. Krijgt of stelt de ruis in.
type: docs
weight: 90
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/
---
## OuterGlowEffect.Noise property

Krijgt of stelt de ruis in.

```csharp
public int Noise { get; set; }
```

### Eigendoms-waarde

Het geluid.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Ruis moet worden opgegeven als percentage in het bereik van 0 tot 100 |

### Voorbeelden

De volgende code demonstreert de OuterGlowEffect-ondersteuning.

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

### Zie ook

* class [OuterGlowEffect](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* montage [Aspose.PSD](../../../)


