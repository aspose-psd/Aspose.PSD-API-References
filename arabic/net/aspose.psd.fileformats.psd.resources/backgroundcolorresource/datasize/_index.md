---
title: BackgroundColorResource.DataSize
second_title: Aspose.PSD لمرجع .NET API
description: BackgroundColorResource ملكية. الحصول على حجم بيانات المورد بالبايت.
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
## BackgroundColorResource.DataSize property

الحصول على حجم بيانات المورد بالبايت.

```csharp
public override int DataSize { get; }
```

### Property_Value

حجم بيانات المورد .

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


