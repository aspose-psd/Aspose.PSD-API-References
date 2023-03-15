---
title: BackgroundColorResource.Color
second_title: Aspose.PSD لمرجع .NET API
description: BackgroundColorResource ملكية. الحصول على لون الخلفية أو تعيينه.
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

الحصول على لون الخلفية أو تعيينه.

```csharp
public Color Color { get; set; }
```

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

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* المجسم [Aspose.PSD](../../../)


