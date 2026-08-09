---
title: "التعداد PathOperations"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations enum. العمليات الخاصة بأشكال المسار التي تجمع عمليات بوليانية"
type: docs
weight: 1400
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

العمليات لتجميع أشكال المسار (عمليات بوليانية).

```csharp
public enum PathOperations
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | استبعاد الأشكال المتداخلة (عملية XOR). |
| CombineShapes | `1` | دمج الأشكال (عملية OR). هذه هي القيمة الافتراضية في Photoshop. |
| SubtractFrontShape | `2` | طرح الشكل الأمامي (عملية NOT). |
| IntersectShapeAreas | `3` | تقاطع مناطق الشكل (عملية AND). |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


