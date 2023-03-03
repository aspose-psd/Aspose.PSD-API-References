---
title: LengthRecord.LengthRecord
second_title: Aspose.PSD لمرجع .NET API
description: LengthRecord البناء. يقوم بتهيئة مثيل جديد لملفLengthRecord فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
## LengthRecord(byte[]) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`LengthRecord`](../) فئة .

```csharp
public LengthRecord(byte[] data)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| data | Byte[] | بيانات السجل. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| !:PsdImageArgumentException | بيانات غير صحيحة لإنشاء LengthRecord |

### أنظر أيضا

* class [LengthRecord](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* المجسم [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

يقوم بتهيئة مثيل جديد لملف[`LengthRecord`](../) فئة .

```csharp
public LengthRecord()
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

* class [LengthRecord](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* المجسم [Aspose.PSD](../../../)


