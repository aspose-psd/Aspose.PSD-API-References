---
title: Size
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 120
url: /net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
## OuterGlowEffect.Size property

Gets the blur value in pixels.

```csharp
public int Size { get; }
```

## Property Value

The size.

### Examples

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

* class [OuterGlowEffect](../../outergloweffect)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect)
* assembly [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
