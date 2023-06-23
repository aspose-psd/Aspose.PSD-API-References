---
title: OuterGlowEffect.BlendMode
second_title: Aspose.PSD for .NET API Reference
description: OuterGlowEffect property. Gets or sets the blend mode
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
{{< psd/tize >}}
## OuterGlowEffect.BlendMode property

Gets or sets the blend mode.

```csharp
public BlendMode BlendMode { get; set; }
```

### Property Value

The blend mode.

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


