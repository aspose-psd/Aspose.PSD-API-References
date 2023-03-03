---
title: BackgroundColorResource.Color
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: BackgroundColorResource संपत्त. पृष्ठभूम क रंग प्रप्त य सेट करत है
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

पृष्ठभूमि का रंग प्राप्त या सेट करता है।

```csharp
public Color Color { get; set; }
```

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

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* सभा [Aspose.PSD](../../../)


