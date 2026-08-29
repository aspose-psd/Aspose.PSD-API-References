---
title: "OuterGlowEffect.Noise"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "OuterGlowEffect property. प्राप्त करता है या सेट करता है शोर"
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/
---
{{< psd/tize >}}
## OuterGlowEffect.Noise property

शोर को प्राप्त करता है या सेट करता है।

```csharp
public int Noise { get; set; }
```

### Property Value

शोर।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | शोर को 0 से 100 की सीमा में प्रतिशत के रूप में निर्दिष्ट करना चाहिए |

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


