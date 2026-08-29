---
title: "OuterGlowEffect.FillColor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "OuterGlowEffect property. प्राप्त करता है या सेट करता है रंग"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/
---
{{< psd/tize >}}
## OuterGlowEffect.FillColor property

रंग प्राप्त करता है या सेट करता है।

```csharp
public IFillSettings FillColor { get; set; }
```

### Property Value

रंग।

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

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


