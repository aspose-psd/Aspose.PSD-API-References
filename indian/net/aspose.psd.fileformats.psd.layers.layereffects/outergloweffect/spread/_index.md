---
title: "OuterGlowEffect.Spread"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "OuterGlowEffect property. तीव्रता को प्रतिशत के रूप में प्राप्त करता है या सेट करता है"
type: docs
weight: 130
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/
---
{{< psd/tize >}}
## OuterGlowEffect.Spread property

तीव्रता को प्रतिशत के रूप में प्राप्त करता है या सेट करता है।

```csharp
public int Spread { get; set; }
```

### Property Value

फ़ैलाव।

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

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


