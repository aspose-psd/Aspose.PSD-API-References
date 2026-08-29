---
title: "IVectorPathData.IsDisabled"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية IVectorPathData. يحصل على أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن معطلاً"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/
---
{{< psd/tize >}}
## IVectorPathData.IsDisabled property

يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل معطلاً.

```csharp
public bool IsDisabled { get; set; }
```

### Property Value

`true` إذا كان هذا الكائن معطلاً؛ وإلا `false`.

## أمثلة

يوضح هذا المثال دعم مورد 'WorkingPathResource' في PsdImage.ImageResources للعمل الصحيح لعملية القص.

```csharp
[C#]

// قص الصورة واحفظها.
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

    // قص واحفظ.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// حمّل الصورة المحفوظة وتحقق من التغييرات.
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

### انظر أيضًا

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


