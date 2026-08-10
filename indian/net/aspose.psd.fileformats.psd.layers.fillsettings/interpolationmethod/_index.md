---
title: "एनम InterpolationMethod"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod एनम। Photoshop ग्रेडिएंट इंटरपोलेशन मेथड के लिए पैक्ड fourCC मान। डिस्क्रिप्टर कुंजी gradientsInterpolationMethod"
type: docs
weight: 2160
url: /hi/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

फ़ोटोशॉप ग्रेडिएंट इंटरपोलेशन मेथड के लिए पैक्ड fourCC वैल्यूज़। डिस्क्रिप्टर कुंजी: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — क्लासिक (जब कुंजी अनुपलब्ध हो तो लेगेसी डिफ़ॉल्ट)। |
| Perceptual | `1348825699` | 'Perc' — पर्सेप्चुअल। |
| Linear | `1282306592` | 'Lnr ' — लीनियर (ध्यान दें कि अंत में स्पेस है)। |
| Smooth | `1399680879` | 'Smoo' — स्मूथ। |
| Stripes | `1195986291` | 'GIMs' — स्ट्राइप्स। |

## उदाहरण

निम्नलिखित कोड ग्रेडिएंट रेंडरिंग के समर्थन को स्मूथ मेथड के साथ दर्शाता है।

```csharp
[C#]

string sourceFile = "GradientOverlay.psd";
string outputFile = "output_GradientOverlay.psd";
string outputFilePng = "output_GradientOverlay.png";

var srcMethod = InterpolationMethod.Linear;
var newMethod = InterpolationMethod.Smooth;

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var image = (PsdImage)Image.Load(sourceFile, opt))
{
    // पढ़ें
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // बदलें
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// सहेजे गए डेटा की जाँच करें
using (var image = (PsdImage)Image.Load(outputFile, opt))
{
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;

    AssertAreEqual(newMethod, gradientSettings.InterpolationMethod);
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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


