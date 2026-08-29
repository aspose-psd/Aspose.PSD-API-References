---
title: "GradientMapLayer.GradientSettings"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "GradientMapLayer प्रॉपर्टी। प्राप्त करता है या सेट करता है Gradient settings instance जो GrdmResource instance से पास किया गया है।"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/gradientsettings/
---
{{< psd/tize >}}
## GradientMapLayer.GradientSettings property

Gradient सेटिंग्स इंस्टेंस को प्राप्त करता है या सेट करता है, जो GrdmResource इंस्टेंस से पास किया गया है।

```csharp
public GradientMapSettings GradientSettings { get; set; }
```

## उदाहरण

निम्नलिखित कोड Gradient map लेयर के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "gradient_map_src.psd";
string outputFile = "gradient_map_src_output.psd";

using (PsdImage im = (PsdImage)Image.Load(sourceFile))
{
    // Gradient map एडजस्टमेंट लेयर जोड़ें।
    GradientMapLayer layer = im.AddGradientMapAdjustmentLayer();
    layer.GradientSettings.Reverse = true;
    layer.Update();

    im.Save(outputFile);
}

// सहेजे गए बदलावों की जाँच करें
using (PsdImage im = (PsdImage)Image.Load(outputFile))
{
    GradientMapLayer gradientMapLayer = im.Layers[1] as GradientMapLayer;
    var gradientSettings = gradientMapLayer.GradientSettings;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;

    AssertAreEqual((short)4096, solidGradient.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual("Custom", solidGradient.GradientName);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### देखें भी

* class [GradientMapSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/)
* class [GradientMapLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


