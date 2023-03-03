---
title: Class OuterGlowEffect
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect कक्ष. बहर चमक परत प्रभव
type: docs
weight: 2170
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
## OuterGlowEffect class

बाहरी चमक परत प्रभाव

```csharp
public class OuterGlowEffect : ILayerEffect
```

## गुण

| नाम | विवरण |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | ब्लेंड मोड प्राप्त या सेट करता है। |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | एक प्रकार का प्रभाव टाइप प्राप्त करता है |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | रंग प्राप्त या सेट करता है। |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | कोण को डिग्री में प्राप्त या सेट करता है। |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | एन्टीअलियासिंग प्रभाव सक्षम हो जाता है या सेट हो जाता है |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | एक मान प्राप्त या सेट करता है जो दर्शाता है कि [नॉक आउट] है। |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण दृश्यमान है या नहीं। |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | शोर प्राप्त करता है या सेट करता है। |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | शोर प्राप्त करता है या सेट करता है। |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | अस्पष्टता प्राप्त या सेट करता है। |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | शोर प्राप्त करता है या सेट करता है। |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; } | धुंधला मान पिक्सेल में प्राप्त करता है. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | तीव्रता को प्रतिशत के रूप में प्राप्त या सेट करता है। |

### उदाहरण

निम्न कोड OuterGlowEffect समर्थन प्रदर्शित करता है।

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### यह सभी देखें

* interface [ILayerEffect](../ilayereffect/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* सभा [Aspose.PSD](../../)


