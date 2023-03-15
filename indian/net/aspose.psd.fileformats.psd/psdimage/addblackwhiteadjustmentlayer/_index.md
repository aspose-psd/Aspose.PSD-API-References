---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: PsdImage तरक. कले सफेद समयजन परत जड़त है
type: docs
weight: 290
url: /hi/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

काले सफेद समायोजन परत जोड़ता है।

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### प्रतिलाभ की मात्रा

बनाई गई काली सफेद समायोजन परत।

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

### यह सभी देखें

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)


