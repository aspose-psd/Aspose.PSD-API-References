---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD لمرجع .NET API
description: BackgroundColorResource ملكية. يحصل على الحد الأدنى من إصدار PSD المطلوب.
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

يحصل على الحد الأدنى من إصدار PSD المطلوب.

```csharp
public override int MinimalVersion { get; }
```

### Property_Value

الحد الأدنى من إصدار PSD .

### أمثلة

يوضح المثال التالي دعم مورد BackgroundColorResource.

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

### أنظر أيضا

* class [BackgroundColorResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* المجسم [Aspose.PSD](../../../)


