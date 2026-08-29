---
title: "क्लास LayerStateEffects"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerStateEffects क्लास। लेयर स्टेट इफ़ेक्ट्स"
type: docs
weight: 1970
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---
{{< psd/tize >}}
## LayerStateEffects class

लेयर स्टेट प्रभाव।

```csharp
public class LayerStateEffects
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/) { get; } | लेयर इफ़ेक्ट्स प्राप्त करता है। |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/isvisible/) { get; set; } | एक मान को प्राप्त करता है या सेट करता है जो यह दर्शाता है कि यह इंस्टेंस दृश्यमान है या नहीं। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/)() | कलर ओवरले इफ़ेक्ट जोड़ता है। |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/)() | ड्रॉप शैडो इफ़ेक्ट जोड़ता है। |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/)() | ग्रेडिएंट ओवरले इफ़ेक्ट जोड़ता है। |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/)() | इंटर शैडो इफ़ेक्ट जोड़ता है। |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/)() | आउटर ग्लो इफ़ेक्ट जोड़ता है। |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/)() | पैटर्न ओवरले इफ़ेक्ट जोड़ता है। |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/)(FillType) | स्ट्रोक इफ़ेक्ट जोड़ता है। |
| [ClearLayerStyle](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/clearlayerstyle/)() | सभी लेयर स्टाइल इफ़ेक्ट्स साफ़ करता है। |
| [RemoveEffectAt](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/removeeffectat/)(int) | विशिष्ट इंडेक्स पर लेयर इफ़ेक्ट को हटाता है। |

## उदाहरण

निम्नलिखित कोड टाइमलाइन फ्रेम्स में इफ़ेक्ट्स के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


