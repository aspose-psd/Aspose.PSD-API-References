---
title: OuterGlowEffect.Jitter
second_title: Aspose.PSD for .NET API Reference
description: OuterGlowEffect property. Gets or sets the noise
type: docs
weight: 80
url: /net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/
---
{{< psd/tize >}}
## OuterGlowEffect.Jitter property

Gets or sets the noise.

```csharp
public int Jitter { get; set; }
```

### Property Value

The noise.

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Noise must be specified as percentage in range from 0 to 100 |

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* assembly [Aspose.PSD](../../../)


