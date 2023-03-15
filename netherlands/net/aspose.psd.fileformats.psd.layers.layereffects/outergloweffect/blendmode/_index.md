---
title: OuterGlowEffect.BlendMode
second_title: Aspose.PSD voor .NET API-referentie
description: OuterGlowEffect eigendom. Krijgt of stelt de overvloeimodus in.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
## OuterGlowEffect.BlendMode property

Krijgt of stelt de overvloeimodus in.

```csharp
public BlendMode BlendMode { get; set; }
```

### Eigendoms-waarde

De mengmodus.

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* montage [Aspose.PSD](../../../)


