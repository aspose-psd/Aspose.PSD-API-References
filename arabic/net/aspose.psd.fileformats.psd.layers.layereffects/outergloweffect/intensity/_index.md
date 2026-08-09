---
title: "OuterGlowEffect.Intensity"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية OuterGlowEffect. يحصل على أو يضبط الزاوية بالدرجات"
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
{{< psd/tize >}}
## OuterGlowEffect.Intensity property

يحصل أو يضبط الزاوية بالدرجات.

```csharp
public int Intensity { get; set; }
```

### Property Value

الزاوية.

## أمثلة

يوضح الشيفرة التالية دعم OuterGlowEffect.

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

### انظر أيضًا

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


