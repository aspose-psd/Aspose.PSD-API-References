---
title: "क्लास InnerShadowEffect"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect क्लास। इंटीरियर शैडो लेयर इफ़ेक्ट"
type: docs
weight: 2350
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
{{< psd/tize >}}
## InnerShadowEffect class

इनर शैडो लेयर इफ़ेक्ट

```csharp
public class InnerShadowEffect : IShadowEffect
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | डिग्री में कोण को प्राप्त करता है या सेट करता है। |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | ब्लेंड मोड को प्राप्त करता है या सेट करता है। |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | रंग प्राप्त करता है या सेट करता है। |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | पिक्सेल में दूरी को प्राप्त करता है या सेट करता है। |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | इफ़ेक्ट का प्रकार प्राप्त करता है। |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | एक मान को प्राप्त करता है या सेट करता है जो यह दर्शाता है कि यह इंस्टेंस दृश्यमान है या नहीं। |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | शोर को प्राप्त करता है या सेट करता है। |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | अपारदर्शिता प्राप्त करता है या सेट करता है। |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | पिक्सेल में ब्लर मान को प्राप्त करता है या सेट करता है। |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | स्प्रेड (चोक) को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | एक मान को प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [use this angle in all of the layer effects]। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/geteffectbounds/)(Rectangle, int) | इनपुट लेयर पिक्सेल सीमाओं के आधार पर इफ़ेक्ट पिक्सेल की सीमाओं की गणना करता है और प्राप्त करता है। |

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

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


