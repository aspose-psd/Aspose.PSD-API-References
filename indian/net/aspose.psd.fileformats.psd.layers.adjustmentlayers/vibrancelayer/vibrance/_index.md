---
title: "VibranceLayer.Vibrance"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VibranceLayer प्रॉपर्टी। वैब्रेंस प्राप्त करता है या सेट करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

वाइब्रेंस प्राप्त करता है या सेट करता है।

```csharp
public int Vibrance { get; set; }
```

### Property Value

वैब्रेंस।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | वैब्रेंस -180 से +180 की सीमा में होना चाहिए |

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

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


