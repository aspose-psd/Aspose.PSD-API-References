---
title: VibAResource.Save
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VibAResource तरक. संसधन क नर्दष्ट स्ट्रम कंटेनर में सहेजत है
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
## VibAResource.Save method

संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है।

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | StreamContainer | सहेजा जाने वाला स्ट्रीम कंटेनर. |
| psdVersion | Int32 | पीएसडी संस्करण। |

### उदाहरण

निम्न कोड उदाहरण VibAResource संसाधन के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

// रनटाइम पर कंपन संसाधन पढ़ने और लिखने के समर्थन का उदाहरण।
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

### यह सभी देखें

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* सभा [Aspose.PSD](../../../)


