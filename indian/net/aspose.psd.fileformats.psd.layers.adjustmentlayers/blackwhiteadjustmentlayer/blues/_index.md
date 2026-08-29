---
title: "BlackWhiteAdjustmentLayer.Blues"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BlackWhiteAdjustmentLayer प्रॉपर्टी। नीले मान को प्राप्त करता है या सेट करता है।"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/blues/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.Blues property

ब्लू मान को प्राप्त करता है या सेट करता है।

```csharp
public int Blues { get; set; }
```

### Property Value

ब्लूज़ मान।

## उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि आप रनटाइम में Aspose.PSD में ब्लैक व्हाइट एडजस्टमेंट लेयर कैसे जोड़ सकते हैं।

```csharp
[C#]

string sourceFileName = "Stripes.psd";
string outputFileName = "OutputStripes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    BlackWhiteAdjustmentLayer newLayer = image.AddBlackWhiteAdjustmentLayer();
    newLayer.Name = "BlackWhiteAdjustmentLayer";
    newLayer.Reds = 22;
    newLayer.Yellows = 92;
    newLayer.Greens = 70;
    newLayer.Cyans = 79;
    newLayer.Blues = 7;
    newLayer.Magentas = 28;

    image.Save(outputFileName, new PsdOptions());
}
```

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


