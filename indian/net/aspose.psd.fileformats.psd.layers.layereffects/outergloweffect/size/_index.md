---
title: OuterGlowEffect.Size
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: OuterGlowEffect संपत्त. धुंधल मन पक्सेल में प्रप्त करत है.
type: docs
weight: 120
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
## OuterGlowEffect.Size property

धुंधला मान पिक्सेल में प्राप्त करता है.

```csharp
public int Size { get; }
```

### संपत्ति मूल्य

आकार।

### उदाहरण

निम्न कोड OuterGlowEffect समर्थन प्रदर्शित करता है।

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

### यह सभी देखें

* class [OuterGlowEffect](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* सभा [Aspose.PSD](../../../)


