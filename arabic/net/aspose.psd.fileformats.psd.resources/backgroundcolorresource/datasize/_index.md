---
title: "BackgroundColorResource.DataSize"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية BackgroundColorResource. يحصل على حجم بيانات المورد بالبايت"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
{{< psd/tize >}}
## BackgroundColorResource.DataSize property

يحصل على حجم بيانات المورد بالبايت.

```csharp
public override int DataSize { get; }
```

### Property Value

حجم بيانات المورد.

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


