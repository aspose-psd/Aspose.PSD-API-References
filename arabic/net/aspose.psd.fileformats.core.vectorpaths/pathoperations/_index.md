---
title: Enum PathOperations
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations تعداد. عمليات دمج أشكال المسار العمليات المنطقية .
type: docs
weight: 1390
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

عمليات دمج أشكال المسار (العمليات المنطقية) .

```csharp
public enum PathOperations
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | استبعاد الأشكال المتداخلة (عملية XOR) . |
| CombineShapes | `1` | دمج الأشكال (عملية أو). هذه هي القيمة الافتراضية في Photoshop. |
| SubtractFrontShape | `2` | اطرح الشكل الأمامي (ليس عملية) . |
| IntersectShapeAreas | `3` | مناطق الشكل المتقاطعة (والتشغيل) . |

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

* مساحة الاسم [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* المجسم [Aspose.PSD](../../)


