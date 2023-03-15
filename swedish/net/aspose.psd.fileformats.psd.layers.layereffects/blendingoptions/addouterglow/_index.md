---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD för .NET API-referens
description: BlendingOptions metod. Lägger till den yttre glödeffekten.
type: docs
weight: 60
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

Lägger till den yttre glödeffekten.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Returvärde

Skapad[`OuterGlowEffect`](../../outergloweffect/) objekt

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* hopsättning [Aspose.PSD](../../../)


