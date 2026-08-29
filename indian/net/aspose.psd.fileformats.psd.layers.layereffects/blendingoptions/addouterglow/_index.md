---
title: "BlendingOptions.AddOuterGlow"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BlendingOptions मेथड। बाहरी चमक इफ़ेक्ट जोड़ता है"
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
{{< psd/tize >}}
## BlendingOptions.AddOuterGlow method

आउटर ग्लो इफ़ेक्ट जोड़ता है।

```csharp
public OuterGlowEffect AddOuterGlow()
```

### रिटर्न वैल्यू

बनाया गया [`OuterGlowEffect`](../../outergloweffect/) ऑब्जेक्ट

## उदाहरण

निम्नलिखित कोड OuterGlowEffect समर्थन को दर्शाता है।

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

### देखें भी

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


