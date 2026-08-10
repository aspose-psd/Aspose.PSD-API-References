---
title: "BackgroundColorResource.Color"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BackgroundColorResource प्रॉपर्टी। बैकग्राउंड कलर प्राप्त करता है या सेट करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
{{< psd/tize >}}
## BackgroundColorResource.Color property

पृष्ठभूमि रंग को प्राप्त करता है या सेट करता है।

```csharp
public Color Color { get; set; }
```

## उदाहरण

निम्नलिखित उदाहरण BackgroundColorResource रिसोर्स के समर्थन को दर्शाता है।

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

    // BackgroundColorResource को अपडेट करें
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### देखें भी

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


