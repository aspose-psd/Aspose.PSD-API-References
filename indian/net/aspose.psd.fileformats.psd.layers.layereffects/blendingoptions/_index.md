---
title: "क्लास BlendingOptions"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions क्लास। BlendingOptions। यह BaseFxResource के लिए एक रैपर है जो लेयर इफ़ेक्ट्स के लिए API प्रदान करता है।"
type: docs
weight: 2290
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
{{< psd/tize >}}
## BlendingOptions class

BlendingOptions। यह BaseFxResource के लिए एक रैपर है जो लेयर इफ़ेक्ट्स के लिए API प्रदान करता है।

```csharp
public class BlendingOptions
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AreEffectsEnabled](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/) { get; set; } | सभी लेयर इफ़ेक्ट्स की दृश्यता को प्राप्त करता है या सेट करता है। |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; set; } | इफ़ेक्ट्स को प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | कलर ओवरले जोड़ता है। |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | ड्रॉप शैडो इफ़ेक्ट जोड़ता है। |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | ग्रेडिएंट ओवरले जोड़ता है। |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | इंटर शैडो इफ़ेक्ट जोड़ता है। |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | आउटर ग्लो इफ़ेक्ट जोड़ता है। |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | पैटर्न ओवरले जोड़ता है। |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | स्ट्रोक इफ़ेक्ट जोड़ता है। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि इंटीरियर शैडो लेयर इफ़ेक्ट की सेटिंग्स को कैसे बदलें।

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


