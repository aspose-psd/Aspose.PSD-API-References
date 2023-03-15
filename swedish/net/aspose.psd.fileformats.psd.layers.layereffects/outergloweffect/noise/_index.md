---
title: OuterGlowEffect.Noise
second_title: Aspose.PSD för .NET API-referens
description: OuterGlowEffect fast egendom. Får eller ställer in bruset.
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/
---
## OuterGlowEffect.Noise property

Får eller ställer in bruset.

```csharp
public int Noise { get; set; }
```

### Fastighetsvärde

Bullret.

### Undantag

| undantag | skick |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Brus måste anges som procent i intervallet 0 till 100 |

### Exempel

Följande kod visar OuterGlowEffect-stödet.

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

### Se även

* class [OuterGlowEffect](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* hopsättning [Aspose.PSD](../../../)


