---
title: BorderInformationResource.Unit
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: BorderInformationResource संपत्त. सम इकइयं क प्रप्त य सेट करत है
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
## BorderInformationResource.Unit property

सीमा इकाइयों को प्राप्त या सेट करता है।

```csharp
public PhysicalUnit Unit { get; set; }
```

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

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* सभा [Aspose.PSD](../../../)


