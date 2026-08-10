---
title: "VibAResource.Length"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VibAResource प्रॉपर्टी। बाइट्स में लेयर संसाधन की लंबाई प्राप्त करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/
---
{{< psd/tize >}}
## VibAResource.Length property

बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है।

```csharp
public override int Length { get; }
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


