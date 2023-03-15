---
title: WorkingPathResource.WorkingPathResource
second_title: Aspose.PSD لمرجع .NET API
description: WorkingPathResource البناء. يقوم بتهيئة مثيل جديد لملفWorkingPathResource فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
## WorkingPathResource constructor

يقوم بتهيئة مثيل جديد لملف[`WorkingPathResource`](../) فئة .

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| dataBytes | Byte[] | بيانات مسار المتجه. |

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

* class [WorkingPathResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* المجسم [Aspose.PSD](../../../)


