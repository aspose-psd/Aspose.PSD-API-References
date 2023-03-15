---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: BlackWhiteAdjustmentLayer संपत्त. एक मन प्रप्त करत है य सेट करत है ज दर्शत है क tint color क उपयग कय गय है
type: docs
weight: 120
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [tint color] का उपयोग किया गया है।

```csharp
public bool UseTint { get; set; }
```

### संपत्ति मूल्य

`सत्य` अगर इस्तेमाल किया [टिंट रंग]; अन्यथा,`असत्य` .

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


