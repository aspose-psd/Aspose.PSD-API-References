---
title: "क्लास GradientMapSettings"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientMapSettings क्लास। ग्रेडिएंट मैप लेयर के लिए ग्रेडिएंट सेटिंग्स क्लास। इसमें ग्रेडिएंट के दोनों प्रकार—सॉलिड और नॉइज़—के सामान्य प्रॉपर्टीज़ शामिल हैं।"
type: docs
weight: 2080
url: /hi/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/
---
{{< psd/tize >}}
## GradientMapSettings class

ग्रेडिएंट मैप लेयर के लिए ग्रेडिएंट सेटिंग्स क्लास। यह दोनों प्रकार के ग्रेडिएंट (सॉलिड और नॉइज़) के लिए सामान्य प्रॉपर्टीज़ शामिल करता है।

```csharp
public class GradientMapSettings
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [GradientMapSettings](gradientmapsettings/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/dither/) { get; set; } | यह संकेत करने वाला मान प्राप्त करता या सेट करता है कि यह [`GradientFillSettings`](../gradientfillsettings/) डिथर है या नहीं। |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/gradient/) { get; set; } | विशिष्ट ग्रेडिएंट डिफिनिशन इंस्टेंस (सॉलिड/नॉइज़) प्राप्त करता या सेट करता है। |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/interpolationmethod/) { get; set; } | ग्रेडिएंट के लिए इंटरपोलेशन मेथड प्राप्त करता या सेट करता है। |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/reverse/) { get; set; } | यह संकेत करने वाला मान प्राप्त करता या सेट करता है कि यह [`GradientFillSettings`](../gradientfillsettings/) रिवर्स है या नहीं। |

## उदाहरण

स्ट्रोक फ़िल इफ़ेक्ट्स में नॉइज़ और सॉलिड ग्रेडिएंट सेटिंग्स को पढ़ने और संशोधित करने का प्रदर्शन करता है।

```csharp
[C#]

string inputFile = "StrokeNoise.psd";
string outputFile = "output.psd";

var loadOptions = new PsdLoadOptions() { LoadEffectsResource = true };

using (PsdImage image = (PsdImage)Image.Load(inputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // सामान्य ग्रेडिएंट फ़िल सेटिंग्स प्रॉपर्टीज़ की जाँच करें
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(true, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(true, gradientFillSettings.Dither);
    AssertAreEqual(true, gradientFillSettings.Reverse);
    AssertAreEqual(116.0, gradientFillSettings.Angle);
    AssertAreEqual(122, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Angle, gradientFillSettings.GradientType);

    // नॉइज़ ग्रेडिएंट प्रॉपर्टीज़ की जाँच करें
    NoiseGradient noiseGradient = gradientFillSettings.Gradient as NoiseGradient;
    AssertIsNotNull(noiseGradient);
    AssertAreEqual(GradientKind.Noise, noiseGradient.GradientMode);
    AssertAreEqual(2107422935, noiseGradient.RndNumberSeed);
    AssertAreEqual(false, noiseGradient.ShowTransparency);
    AssertAreEqual(false, noiseGradient.UseVectorColor);
    AssertAreEqual(2048, noiseGradient.Roughness);
    AssertAreEqual(NoiseColorModel.RGB, noiseGradient.ColorModel);
    AssertAreEqual((long)0, noiseGradient.MinimumColor.GetAsLong());
    AssertAreEqual(28147819798528050, noiseGradient.MaximumColor.GetAsLong());

    // ग्रेडिएंट सेटिंग्स बदलें
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Dither = false;
    gradientFillSettings.Reverse = false;
    gradientFillSettings.Angle = 30;
    gradientFillSettings.Scale = 80;
    gradientFillSettings.GradientType = GradientType.Linear;

    var solidGradient = new SolidGradient();
    solidGradient.Interpolation = 2048;
    solidGradient.ColorPoints[0].RawColor.Components[0].Value = 255; // A
    solidGradient.ColorPoints[0].RawColor.Components[1].Value = 255; // R 
    solidGradient.ColorPoints[0].RawColor.Components[2].Value = 0;   // G
    solidGradient.ColorPoints[0].RawColor.Components[3].Value = 0;   // B
    solidGradient.TransparencyPoints[1].Opacity = 50;
    gradientFillSettings.Gradient = solidGradient;

    image.Save(outputFile);
}

// सहेजे गए बदलावों की जाँच करें
using (PsdImage image = (PsdImage)Image.Load(outputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // सामान्य ग्रेडिएंट फ़िल सेटिंग्स प्रॉपर्टीज़ की जाँच करें
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(false, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(false, gradientFillSettings.Dither);
    AssertAreEqual(false, gradientFillSettings.Reverse);
    AssertAreEqual(30.0, gradientFillSettings.Angle);
    AssertAreEqual(80, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Linear, gradientFillSettings.GradientType);

    SolidGradient solidGradient = gradientFillSettings.Gradient as SolidGradient;
    AssertIsNotNull(solidGradient);
    AssertAreEqual((short)2048, solidGradient.Interpolation);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[0].Value);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[1].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[2].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[3].Value);
    AssertAreEqual(50.0, solidGradient.TransparencyPoints[1].Opacity);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


