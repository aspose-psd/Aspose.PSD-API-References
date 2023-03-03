---
title: OuterGlowEffect.FillColor
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: OuterGlowEffect संपत्त. रंग प्रप्त य सेट करत है
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/
---
## OuterGlowEffect.FillColor property

रंग प्राप्त या सेट करता है।

```csharp
public IFillSettings FillColor { get; set; }
```

### संपत्ति मूल्य

रंग.

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

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [OuterGlowEffect](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* सभा [Aspose.PSD](../../../)


