---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: PsdImage तरक. वइब्रेंस समयजन परत जड़त है.
type: docs
weight: 430
url: /hi/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

वाइब्रेंस समायोजन परत जोड़ता है.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### प्रतिलाभ की मात्रा

एक नव निर्मित वाइब्रेंस परत।

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)


