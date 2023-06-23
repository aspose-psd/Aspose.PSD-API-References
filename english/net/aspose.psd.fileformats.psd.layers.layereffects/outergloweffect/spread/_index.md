---
title: OuterGlowEffect.Spread
second_title: Aspose.PSD for .NET API Reference
description: OuterGlowEffect property. Gets or sets the intensity as a percent
type: docs
weight: 130
url: /net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/
---
{{< psd/tize >}}
## OuterGlowEffect.Spread property

Gets or sets the intensity as a percent.

```csharp
public int Spread { get; set; }
```

### Property Value

The spread.

## Examples

The following code demonstrates the OuterGlowEffect support.

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

### See Also

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


