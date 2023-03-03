---
title: BorderInformationResource.MinimalVersion
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: BorderInformationResource संपत्त. न्यूनतम आवश्यक PSD संस्करण प्रप्त करत है
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
## BorderInformationResource.MinimalVersion property

न्यूनतम आवश्यक PSD संस्करण प्राप्त करता है।

```csharp
public override int MinimalVersion { get; }
```

### संपत्ति मूल्य

न्यूनतम PSD संस्करण।

### उदाहरण

निम्न उदाहरण BorderInformationResource संसाधन के समर्थन को प्रदर्शित करता है।

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

    // अद्यतन सीमा सूचना संसाधन
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### यह सभी देखें

* class [BorderInformationResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* सभा [Aspose.PSD](../../../)


