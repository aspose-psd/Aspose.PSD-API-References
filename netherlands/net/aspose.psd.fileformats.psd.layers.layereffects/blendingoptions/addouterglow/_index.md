---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD voor .NET API-referentie
description: BlendingOptions methode. Voegt het buitenste gloedeffect toe.
type: docs
weight: 60
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

Voegt het buitenste gloedeffect toe.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Winstwaarde

Gemaakt[`OuterGlowEffect`](../../outergloweffect/) object

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* montage [Aspose.PSD](../../../)


