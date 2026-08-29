---
title: "OuterGlowEffect.BlendMode"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "OuterGlowEffect property. प्राप्त करता है या सेट करता है ब्लेंड मोड"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
{{< psd/tize >}}
## OuterGlowEffect.BlendMode property

ब्लेंड मोड को प्राप्त करता है या सेट करता है।

```csharp
public BlendMode BlendMode { get; set; }
```

### Property Value

ब्लेंड मोड।

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


