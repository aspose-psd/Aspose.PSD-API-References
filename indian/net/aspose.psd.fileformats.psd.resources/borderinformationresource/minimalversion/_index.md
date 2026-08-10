---
title: "BorderInformationResource.MinimalVersion"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BorderInformationResource प्रॉपर्टी। न्यूनतम आवश्यक PSD संस्करण प्राप्त करता है"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
{{< psd/tize >}}
## BorderInformationResource.MinimalVersion property

आवश्यक न्यूनतम PSD संस्करण को प्राप्त करता है।

```csharp
public override int MinimalVersion { get; }
```

### Property Value

न्यूनतम PSD संस्करण.

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


