---
title: Interface IVectorPathData
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData واجهه المستخدم. واجهة الوصول إلى بيانات مسار المتجه.
type: docs
weight: 1350
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

واجهة الوصول إلى بيانات مسار المتجه.

```csharp
public interface IVectorPathData
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل معطلاً. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل معكوسًا. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل غير مرتبط. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | الحصول على أو تعيين سجلات المسار . |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | الحصول على الإصدار أو تحديده. |

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

* مساحة الاسم [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* المجسم [Aspose.PSD](../../)


