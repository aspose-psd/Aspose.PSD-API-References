---
title: OuterGlowEffect.Noise
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: OuterGlowEffect संपत्त. शर प्रप्त करत है य सेट करत है
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/
---
## OuterGlowEffect.Noise property

शोर प्राप्त करता है या सेट करता है।

```csharp
public int Noise { get; set; }
```

### संपत्ति मूल्य

शोर।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | शोर को 0 से 100 की सीमा में प्रतिशत के रूप में निर्दिष्ट किया जाना चाहिए |

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


