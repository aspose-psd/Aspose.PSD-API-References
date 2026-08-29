---
title: "क्लास DropShadowEffect"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect क्लास। ड्रॉप शैडो लेयर इफ़ेक्ट"
type: docs
weight: 2310
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
{{< psd/tize >}}
## DropShadowEffect class

ड्रॉप शैडो लेयर इफ़ेक्ट

```csharp
public class DropShadowEffect : IShadowEffect
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | डिग्री में कोण को प्राप्त करता है या सेट करता है। |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | ब्लेंड मोड को प्राप्त करता है या सेट करता है। |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | रंग प्राप्त करता है या सेट करता है। |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | पिक्सेल में दूरी को प्राप्त करता है या सेट करता है। |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | इफ़ेक्ट का प्रकार प्राप्त करता है। |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | एक मान को प्राप्त करता है या सेट करता है जो यह दर्शाता है कि यह इंस्टेंस दृश्यमान है या नहीं। |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [knocks out]। |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | शोर को प्राप्त करता है या सेट करता है। |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | अपारदर्शिता प्राप्त करता है या सेट करता है। |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | पिक्सेल में ब्लर मान को प्राप्त करता है या सेट करता है। |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | तीव्रता को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | एक मान को प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [use this angle in all of the layer effects]। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/geteffectbounds/)(Rectangle, int) | इनपुट लेयर पिक्सेल सीमाओं के आधार पर इफ़ेक्ट पिक्सेल की सीमाओं की गणना करता है और प्राप्त करता है। |

## उदाहरण

निम्नलिखित कोड PsdImage.GlobalAngle प्रॉपर्टी के समर्थन को दर्शाता है ताकि वैश्विक कोण मान बदला जा सके।

```csharp
[C#]

// जब DropShadowEffect.UseGlobalLight प्रॉपर्टी 'true' हो, तो DropShadowEffect ऑब्जेक्ट PsdImage.GlobalAngle प्रॉपर्टी से कोण मान का उपयोग करता है।

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

निम्नलिखित कोड DropShadowEffect की Opacity प्रॉपर्टी के उपयोग को दर्शाता है।

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // उदाहरण Opacity = 20 के साथ
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // उदाहरण Opacity = 200 के साथ
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### देखें भी

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


