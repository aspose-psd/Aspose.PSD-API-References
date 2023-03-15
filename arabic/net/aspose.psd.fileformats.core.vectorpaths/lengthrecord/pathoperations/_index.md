---
title: LengthRecord.PathOperations
second_title: Aspose.PSD لمرجع .NET API
description: LengthRecord ملكية. الحصول على أو تعيين عمليات المسار.
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/pathoperations/
---
## LengthRecord.PathOperations property

الحصول على أو تعيين عمليات المسار.

```csharp
public PathOperations PathOperations { get; set; }
```

### أمثلة

يوضح المثال التالي من التعليمات البرمجية دعم خصائص LengthRecord الجديدة و PathOperations (العمليات المنطقية) و ShapeIndex و BezierKnotRecordsCount.

```csharp
[C#]

string sourceFilePath = "PathOperationsShape.psd";
string outputFilePath = "out_PathOperationsShape.psd";

using (var im = (PsdImage)Image.Load(sourceFilePath))
{
    VsmsResource resource = null;
    foreach (var layerResource in im.Layers[1].Resources)
    {
        if (layerResource is VsmsResource)
        {
            resource = (VsmsResource)layerResource;
            break;
        }
    }

    LengthRecord lengthRecord0 = (LengthRecord)resource.Paths[2];
    LengthRecord lengthRecord1 = (LengthRecord)resource.Paths[7];
    LengthRecord lengthRecord2 = (LengthRecord)resource.Paths[11];

    // هنا نغير الطريق إلى الجمع بين الأشكال.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### أنظر أيضا

* enum [PathOperations](../../pathoperations/)
* class [LengthRecord](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* المجسم [Aspose.PSD](../../../)


