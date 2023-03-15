---
title: Class WorkingPathResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource فصل. مورد مسار العمل .
type: docs
weight: 3980
url: /ar/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
## WorkingPathResource class

مورد مسار العمل .

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | يقوم بتهيئة مثيل جديد لملف`WorkingPathResource` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | الحصول على حجم بيانات المورد بالبايت. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | الحصول على أو تحديد المعرف الفريد للمورد. |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل معطلاً. |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل معكوسًا. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل غير مرتبط. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | يحصل على الحد الأدنى من إصدار PSD المطلوب. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | الحصول على اسم المورد أو تعيينه. سلسلة باسكال ، مبطن لجعل الحجم زوجياً (يتكون الاسم الفارغ من وحدتي بايت من 0) . |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | الحصول على أو تعيين سجلات المسار . |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | يحصل على توقيع المورد. يجب أن يكون دائمًا "8BIM" . |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | الحصول على حجم كتلة المورد بالبايت بما في ذلك البيانات الخاصة به. |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | الحصول على الإصدار أو تحديده. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | يحفظ كتلة المورد في الدفق المحدد. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | يتحقق من صحة قيم المورد . |

### أمثلة

يوضح هذا المثال دعم مورد "WorkingPathResource" في PsdImage.ImageResources للعمل الصحيح لعملية Crop.

```csharp
[C#]

// صورة المحاصيل وحفظها.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // ابحث عن مورد WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // اقتصاص وحفظ.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// قم بتحميل الصورة المحفوظة وتحقق من التغييرات.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // ابحث عن مورد WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### أنظر أيضا

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* المجسم [Aspose.PSD](../../)


