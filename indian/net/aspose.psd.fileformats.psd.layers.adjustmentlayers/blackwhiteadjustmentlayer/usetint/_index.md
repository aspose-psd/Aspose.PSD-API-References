---
title: "BlackWhiteAdjustmentLayer.UseTint"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BlackWhiteAdjustmentLayer प्रॉपर्टी। एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि टिंट रंग उपयोग किया गया है या नहीं"
type: docs
weight: 120
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.UseTint property

एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [tint color] उपयोग किया गया है या नहीं।

```csharp
public bool UseTint { get; set; }
```

### Property Value

`true` यदि उपयोग किया गया है [tint color]; अन्यथा, `false`।

## उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि आप Aspose.PSD में ब्लैक व्हाइट एडजस्टमेंट लेयर प्रॉपर्टीज़ को कैसे नियंत्रित कर सकते हैं।

```csharp
[C#]

sourceFileName = "BlackWhiteAdjustmentLayerStripesMask.psd";
outputFileName = "OutputBlackWhiteAdjustmentLayerStripesMask.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    var blwhLayer = (BlackWhiteAdjustmentLayer)image.Layers[1];

    blwhLayer.Reds = 15;
    blwhLayer.Yellows = 25;
    blwhLayer.Greens = 35;
    blwhLayer.Cyans = 10;
    blwhLayer.Blues = 50;
    blwhLayer.Magentas = 105;
    blwhLayer.UseTint = true;
    blwhLayer.BwPresetKind = 4;
    blwhLayer.BlackAndWhitePresetFileName = "bwPresetFileName";
    blwhLayer.TintColorRed = 60;
    blwhLayer.TintColorGreen = 80;
    blwhLayer.TintColorBlue = 200;

    image.Save(outputFileName, new PsdOptions());
}
```

### देखें भी

* class [BlackWhiteAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


