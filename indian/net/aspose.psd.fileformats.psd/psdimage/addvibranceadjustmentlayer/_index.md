---
title: "PsdImage.AddVibranceAdjustmentLayer"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdImage method. Vibrance समायोजन लेयर जोड़ता है"
type: docs
weight: 490
url: /hi/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

वाइब्रेंस एडजस्टमेंट लेयर जोड़ता है।

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### रिटर्न वैल्यू

एक नई बनाई गई Vibrance लेयर।

## उदाहरण

निम्नलिखित कोड उदाहरण VibranceLayer लेयर के समर्थन और इस एडजस्टमेंट को संपादित करने की क्षमता को दर्शाता है।

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // एक नया VibranceLayer बनाना
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### देखें भी

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


