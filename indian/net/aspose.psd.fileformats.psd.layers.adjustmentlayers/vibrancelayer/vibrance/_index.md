---
title: VibranceLayer.Vibrance
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VibranceLayer संपत्त. जवंतत प्रप्त य सेट करत है
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
## VibranceLayer.Vibrance property

जीवंतता प्राप्त या सेट करता है।

```csharp
public int Vibrance { get; set; }
```

### संपत्ति मूल्य

जीवंतता।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentOutOfRangeException | कंपन -180 से +180 की सीमा में होना चाहिए |

### उदाहरण

निम्नलिखित कोड उदाहरण वाइब्रेंसलेयर परत के समर्थन और इस समायोजन को संपादित करने की क्षमता को प्रदर्शित करता है।

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // एक नई वाइब्रेंसलेयर बनाना
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### यह सभी देखें

* class [VibranceLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* सभा [Aspose.PSD](../../../)


