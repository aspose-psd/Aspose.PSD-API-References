---
title: OuterGlowEffect.Intensity
second_title: Aspose.PSD för .NET API-referens
description: OuterGlowEffect fast egendom. Hämtar eller ställer in vinkeln i grader.
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
## OuterGlowEffect.Intensity property

Hämtar eller ställer in vinkeln i grader.

```csharp
public int Intensity { get; set; }
```

### Fastighetsvärde

Vinkeln.

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


