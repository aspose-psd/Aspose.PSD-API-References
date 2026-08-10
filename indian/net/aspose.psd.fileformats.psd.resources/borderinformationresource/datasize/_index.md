---
title: "BorderInformationResource.DataSize"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BorderInformationResource प्रॉपर्टी। बाइट्स में संसाधन डेटा आकार प्राप्त करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
{{< psd/tize >}}
## BorderInformationResource.DataSize property

संसाधन डेटा आकार को बाइट्स में प्राप्त करता है।

```csharp
public override int DataSize { get; }
```

### Property Value

संसाधन डेटा आकार.

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

* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


