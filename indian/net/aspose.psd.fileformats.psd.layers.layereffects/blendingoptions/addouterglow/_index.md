---
title: BlendingOptions.AddOuterGlow
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: BlendingOptions तरक. बहर चमक प्रभव जड़त है
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

बाहरी चमक प्रभाव जोड़ता है।

```csharp
public OuterGlowEffect AddOuterGlow()
```

### प्रतिलाभ की मात्रा

बनाया गया[`OuterGlowEffect`](../../outergloweffect/) वस्तु

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* सभा [Aspose.PSD](../../../)


