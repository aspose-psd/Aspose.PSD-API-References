---
title: "LengthRecord.ShapeIndex"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية LengthRecord. يحصل أو يعيّن فهرس الشكل الحالي للمسار في الطبقة"
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/shapeindex/
---
{{< psd/tize >}}
## LengthRecord.ShapeIndex property

يحصل أو يعيّن فهرس الشكل المساري الحالي في الطبقة.

```csharp
public ushort ShapeIndex { get; set; }
```

## أمثلة

يوضح مثال الشيفرة التالي دعم الخصائص الجديدة LengthRecord، وPathOperations (العمليات البوليانية)، وShapeIndex وBezierKnotRecordsCount.

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

    // هنا نغير الطريقة التي نجمع بها الأشكال.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### انظر أيضًا

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


