---
title: "NoiseGradient.ExpansionCount"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "NoiseGradient प्रॉपर्टी। एक्सपैंशन काउंट को प्राप्त करता है या सेट करता है   Photoshop 6.0 के लिए 2"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.gradient/noisegradient/expansioncount/
---
{{< psd/tize >}}
## NoiseGradient.ExpansionCount property

एक्सपैंशन काउंट ( = 2 फ़ॉटोशॉप 6.0 के लिए) को प्राप्त करता है या सेट करता है।

```csharp
public short ExpansionCount { get; set; }
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

* class [NoiseGradient](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../../)


