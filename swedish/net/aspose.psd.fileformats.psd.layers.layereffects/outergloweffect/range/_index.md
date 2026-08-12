---
title: "OuterGlowEffect.Range"
second_title: "Aspose.PSD för .NET API‑referens"
description: "OuterGlowEffect egenskap. Hämtar eller anger bruset"
type: docs
weight: 110
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/
---
{{< psd/tize >}}
## OuterGlowEffect.Range property

Hämtar eller anger brus.

```csharp
public int Range { get; set; }
```

### Property Value

Bruset.

### Undantag

| undantag | villkor |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Brus måste anges som procent i intervallet från 0 till 100 |

## Exempel

Följande kod demonstrerar stöd för OuterGlowEffect.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


