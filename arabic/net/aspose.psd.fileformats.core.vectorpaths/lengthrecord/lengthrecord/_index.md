---
title: "LengthRecord.LengthRecord"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ LengthRecord. يهيئ مثيلًا جديدًا من الفئة LengthRecord"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
{{< psd/tize >}}
## LengthRecord(byte[]) {#constructor_1}

يهيئ مثيلًا جديدًا من الفئة [`LengthRecord`](../).

```csharp
public LengthRecord(byte[] data)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | Byte[] | بيانات السجل. |

### انظر أيضًا

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

يهيئ مثيلًا جديدًا من الفئة [`LengthRecord`](../).

```csharp
public LengthRecord()
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


