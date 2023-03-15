---
title: Class BorderInformationResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource فصل. المورد بمعلومات حدية لإعدادات طباعة الصورة .
type: docs
weight: 3650
url: /ar/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
## BorderInformationResource class

المورد بمعلومات حدية لإعدادات طباعة الصورة .

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | الحصول على حجم بيانات المورد بالبايت. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | الحصول على أو تحديد المعرف الفريد للمورد. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | يحصل على الحد الأدنى من إصدار PSD المطلوب. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | الحصول على اسم المورد أو تعيينه. سلسلة باسكال ، مبطن لجعل الحجم زوجياً (يتكون الاسم الفارغ من وحدتي بايت من 0) . |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | يحصل على توقيع المورد. يجب أن يكون دائمًا "8BIM" . |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | الحصول على حجم كتلة المورد بالبايت بما في ذلك البيانات الخاصة به. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | الحصول على أو تعيين وحدات الحدود . |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | الحصول على عرض الحد أو تحديده . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | يحفظ كتلة المورد في الدفق المحدد. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | يتحقق من صحة قيم المورد . |

### أمثلة

يوضح المثال التالي دعم مورد BorderInformationResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // تحديث BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### أنظر أيضا

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* المجسم [Aspose.PSD](../../)


