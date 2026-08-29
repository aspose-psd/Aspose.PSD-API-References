---
title: "الفئة BorderInformationResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource. المورد الذي يحتوي على معلومات الحدود لإعدادات طباعة الصورة."
type: docs
weight: 4110
url: /ar/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
{{< psd/tize >}}
## BorderInformationResource class

المورد الذي يحتوي على معلومات الحدود لإعدادات طباعة الصورة.

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | يحصل على حجم بيانات المورد بالبايت. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | يحصل أو يضبط المعرف الفريد للمورد. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | يحصل أو يضبط اسم المورد. سلسلة باسكال، مملوءة لتصبح الحجم زوجيًا (اسم فارغ يتكون من بايتين من الصفر). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | يحصل أو يضبط وحدات الحدود. |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | يحصل أو يضبط عرض الحدود. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | يحفظ كتلة المورد إلى الدفق المحدد. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | يتحقق من صحة قيم المورد. |

## أمثلة

المثال التالي يوضح دعم مورد BorderInformationResource.

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

### انظر أيضًا

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


