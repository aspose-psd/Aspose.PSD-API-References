---
title: "BackgroundColorResource.DataSize"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BackgroundColorResource प्रॉपर्टी। बाइट्स में रिसोर्स डेटा आकार प्राप्त करता है"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
{{< psd/tize >}}
## BackgroundColorResource.DataSize property

संसाधन डेटा आकार को बाइट्स में प्राप्त करता है।

```csharp
public override int DataSize { get; }
```

### Property Value

संसाधन डेटा आकार.

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

* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


