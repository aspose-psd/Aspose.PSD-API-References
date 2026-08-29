---
title: "OuterGlowEffect.Spread"
second_title: "Aspose.PSD för .NET API‑referens"
description: "OuterGlowEffect egenskap. Hämtar eller anger intensiteten i procent"
type: docs
weight: 130
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/
---
{{< psd/tize >}}
## OuterGlowEffect.Spread property

Hämtar eller anger intensiteten som procent.

```csharp
public int Spread { get; set; }
```

### Property Value

Spridningen.

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


