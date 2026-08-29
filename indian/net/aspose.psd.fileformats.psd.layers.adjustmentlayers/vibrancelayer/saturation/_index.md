---
title: "VibranceLayer.Saturation"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VibranceLayer प्रॉपर्टी। संतृप्ति प्राप्त करता है या सेट करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
{{< psd/tize >}}
## VibranceLayer.Saturation property

सैचुरेशन प्राप्त करता है या सेट करता है।

```csharp
public int Saturation { get; set; }
```

### Property Value

संतृप्ति।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | संतृप्ति -100 से +100 की सीमा में होनी चाहिए |

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


