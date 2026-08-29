---
title: "BorderInformationResource.Unit"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BorderInformationResource प्रॉपर्टी। बॉर्डर इकाइयों को प्राप्त करता है या सेट करता है"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
{{< psd/tize >}}
## BorderInformationResource.Unit property

बॉर्डर इकाइयों को प्राप्त करता है या सेट करता है।

```csharp
public PhysicalUnit Unit { get; set; }
```

## उदाहरण

निम्नलिखित उदाहरण BorderInformationResource संसाधन के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // BorderInformationResource को अपडेट करें
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### देखें भी

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


