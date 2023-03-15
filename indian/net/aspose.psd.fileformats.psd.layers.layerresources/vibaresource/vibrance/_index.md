---
title: VibAResource.Vibrance
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VibAResource संपत्त. वइब्रेंस वैल्यू प्रप्त य सेट करत है
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/
---
## VibAResource.Vibrance property

वाइब्रेंस वैल्यू प्राप्त या सेट करता है

```csharp
public int Vibrance { get; set; }
```

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

* class [VibAResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* सभा [Aspose.PSD](../../../)


