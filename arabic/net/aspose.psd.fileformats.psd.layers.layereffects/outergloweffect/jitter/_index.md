---
title: "OuterGlowEffect.Jitter"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "OuterGlowEffect property. يحصل أو يضبط الضوضاء"
type: docs
weight: 80
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/
---
{{< psd/tize >}}
## OuterGlowEffect.Jitter property

يحصل أو يضبط الضوضاء.

```csharp
public int Jitter { get; set; }
```

### Property Value

الضوضاء.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | يجب تحديد الضوضاء كنسبة مئوية في النطاق من 0 إلى 100 |

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


