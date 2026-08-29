---
title: "VibAResource.TypeToolKey"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VibAResource फ़ील्ड। टाइप टूल जानकारी कुंजी"
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/
---
{{< psd/tize >}}
## VibAResource.TypeToolKey field

टाइप टूल जानकारी कुंजी।

```csharp
public const int TypeToolKey;
```

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

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


