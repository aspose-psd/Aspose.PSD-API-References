---
title: Class DropShadowEffect
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect कक्ष. ड्रप शैड लेयर प्रभव
type: docs
weight: 2120
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

ड्रॉप शैडो लेयर प्रभाव

```csharp
public class DropShadowEffect : IShadowEffect
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | कोण को डिग्री में प्राप्त या सेट करता है। |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | ब्लेंड मोड प्राप्त या सेट करता है। |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | रंग प्राप्त या सेट करता है। |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | पिक्सेल में दूरी प्राप्त या सेट करता है। |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | एक प्रकार का प्रभाव प्राप्त करता है |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण दृश्यमान है या नहीं। |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | एक मान प्राप्त या सेट करता है जो दर्शाता है कि [नॉक आउट] है। |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | शोर प्राप्त करता है या सेट करता है। |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | अस्पष्टता प्राप्त या सेट करता है। |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | ब्लर मान पिक्सेल में प्राप्त या सेट करता है. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | तीव्रता को प्रतिशत के रूप में प्राप्त या सेट करता है। |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि क्या [सभी परत प्रभावों में इस कोण का उपयोग करें]. |

### उदाहरण

निम्न कोड वैश्विक कोण मान को बदलने के लिए PsdImage.GlobalAngle गुण के लिए समर्थन प्रदर्शित करता है।

```csharp
[C#]

// जब DropShadowEffect.UseGlobalLight गुण 'true' है, तो DropShadowEffect ऑब्जेक्ट PsdImage.GlobalAngle गुण से कोण मान का उपयोग करता है।

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

निम्न कोड DropShadowEffect के अपारदर्शिता गुण का उपयोग करके प्रदर्शित करता है।

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

    // उदाहरण अपारदर्शिता = 20 के साथ
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // उदाहरण अपारदर्शिता = 20 के साथ0
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### यह सभी देखें

* interface [IShadowEffect](../ishadoweffect/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* सभा [Aspose.PSD](../../)


