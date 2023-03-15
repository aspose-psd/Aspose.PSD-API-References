---
title: OuterGlowEffect.Size
second_title: Aspose.PSD voor .NET API-referentie
description: OuterGlowEffect eigendom. Krijgt de vervagingswaarde in pixels.
type: docs
weight: 120
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
## OuterGlowEffect.Size property

Krijgt de vervagingswaarde in pixels.

```csharp
public int Size { get; }
```

### Eigendoms-waarde

De grootte.

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


