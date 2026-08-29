---
title: "VibAResource.Save"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VibAResource मेथड। रिसोर्स को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है"
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
{{< psd/tize >}}
## VibAResource.Save method

निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है।

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| streamContainer | StreamContainer | सहेजने के लिए स्ट्रीम कंटेनर। |
| psdVersion | Int32 | PSD संस्करण। |

## उदाहरण

निम्नलिखित कोड उदाहरण VibAResource संसाधन के समर्थन को दर्शाता है।

```csharp
[C#]

// रनटाइम पर पढ़ने और लिखने वाले Vibration संसाधन के समर्थन का उदाहरण।
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### देखें भी

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


