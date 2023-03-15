---
title: BlackWhiteAdjustmentLayer.BwPresetKind
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: BlackWhiteAdjustmentLayer संपत्त. ब्लैक एंड व्हइट प्रसेट प्रकर मन प्रप्त य सेट करत है
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/bwpresetkind/
---
## BlackWhiteAdjustmentLayer.BwPresetKind property

ब्लैक एंड व्हाइट प्रीसेट प्रकार मान प्राप्त या सेट करता है।

```csharp
public int BwPresetKind { get; set; }
```

### संपत्ति मूल्य

ब्लैक एंड व्हाइट प्रीसेट प्रकार का मान।

### उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि आप Aspose.PSD में काले सफेद समायोजन परत गुणों में हेरफेर कैसे कर सकते हैं

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

### यह सभी देखें

* class [BlackWhiteAdjustmentLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* सभा [Aspose.PSD](../../../)


