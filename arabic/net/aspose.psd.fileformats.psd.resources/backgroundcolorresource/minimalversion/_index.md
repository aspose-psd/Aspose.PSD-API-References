---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية BackgroundColorResource. يحصل على الحد الأدنى المطلوب لإصدار PSD"
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

يحصل على الحد الأدنى لإصدار PSD المطلوب.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

إصدار PSD الأدنى.

## أمثلة

المثال التالي يوضح دعم المورد BackgroundColorResource.

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

    // تحديث BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### انظر أيضًا

* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


