---
title: Class BackgroundColorResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.BackgroundColorResource فصل. المورد بمعلومات حدية لإعدادات طباعة الصورة .
type: docs
weight: 3640
url: /ar/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---
## BackgroundColorResource class

المورد بمعلومات حدية لإعدادات طباعة الصورة .

```csharp
public sealed class BackgroundColorResource : ResourceBlock
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [BackgroundColorResource](backgroundcolorresource/)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/) { get; set; } | الحصول على لون الخلفية أو تعيينه. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/) { get; } | الحصول على حجم بيانات المورد بالبايت. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | الحصول على أو تحديد المعرف الفريد للمورد. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/) { get; } | يحصل على الحد الأدنى من إصدار PSD المطلوب. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | الحصول على اسم المورد أو تعيينه. سلسلة باسكال ، مبطن لجعل الحجم زوجياً (يتكون الاسم الفارغ من وحدتي بايت من 0) . |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | يحصل على توقيع المورد. يجب أن يكون دائمًا "8BIM" . |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | الحصول على حجم كتلة المورد بالبايت بما في ذلك البيانات الخاصة به. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | يحفظ كتلة المورد في الدفق المحدد. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | يتحقق من صحة قيم المورد . |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* المجسم [Aspose.PSD](../../)


