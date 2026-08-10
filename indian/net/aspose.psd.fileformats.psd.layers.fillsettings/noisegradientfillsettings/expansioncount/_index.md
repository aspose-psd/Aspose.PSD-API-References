---
title: "NoiseGradientFillSettings.ExpansionCount"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "NoiseGradientFillSettings प्रॉपर्टी। एक्सपैंशन काउंट को प्राप्त करता है या सेट करता है   2 फ़ॉटोशॉप 6.0 के लिए"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/expansioncount/
---
{{< psd/tize >}}
## NoiseGradientFillSettings.ExpansionCount property

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
    GradientFillSettings gradientSettings = (GradientFillSettings)gradientMapLayer.GradientSettings;

    AssertAreEqual(90.0, gradientSettings.Angle);
    AssertAreEqual((short)4096, gradientSettings.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(true, gradientSettings.AlignWithLayer);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual(GradientType.Linear, gradientSettings.GradientType);
    AssertAreEqual(100, gradientSettings.Scale);
    AssertAreEqual(0.0, gradientSettings.HorizontalOffset);
    AssertAreEqual(0.0, gradientSettings.VerticalOffset);
    AssertAreEqual("Custom", gradientSettings.GradientName);
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

* class [NoiseGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


