---
title: BlackWhiteAdjustmentLayer.Reds
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: BlackWhiteAdjustmentLayer संपत्त. रेड वैल्यू प्रप्त य सेट करत है
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/reds/
---
## BlackWhiteAdjustmentLayer.Reds property

रेड वैल्यू प्राप्त या सेट करता है।

```csharp
public int Reds { get; set; }
```

### संपत्ति मूल्य

लाल मान.

### उदाहरण

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में रनटाइम पर काले सफेद समायोजन परत को कैसे जोड़ सकते हैं

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


