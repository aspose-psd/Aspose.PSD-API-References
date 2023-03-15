---
title: BackgroundColorResource.MinimalVersion
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: BackgroundColorResource संपत्त. न्यूनतम आवश्यक PSD संस्करण प्रप्त करत है
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

न्यूनतम आवश्यक PSD संस्करण प्राप्त करता है।

```csharp
public override int MinimalVersion { get; }
```

### संपत्ति मूल्य

न्यूनतम PSD संस्करण।

### उदाहरण

निम्न उदाहरण पृष्ठभूमिरंग संसाधन संसाधन के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // अद्यतन पृष्ठभूमि रंग संसाधन
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### यह सभी देखें

* class [BackgroundColorResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* सभा [Aspose.PSD](../../../)


