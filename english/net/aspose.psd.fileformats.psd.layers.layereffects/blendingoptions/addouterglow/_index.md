---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD for .NET API Reference
description: BlendingOptions method. Adds the outer glow effect
type: docs
weight: 70
url: /net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
{{< psd/tize >}}
## BlendingOptions.AddOuterGlow method

Adds the outer glow effect.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Return Value

Created [`OuterGlowEffect`](../../outergloweffect/) object

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


