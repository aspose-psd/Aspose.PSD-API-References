---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BackgroundColorResource प्रॉपर्टी। न्यूनतम आवश्यक PSD संस्करण प्राप्त करता है"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

आवश्यक न्यूनतम PSD संस्करण को प्राप्त करता है।

```csharp
public override int MinimalVersion { get; }
```

### Property Value

न्यूनतम PSD संस्करण.

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


