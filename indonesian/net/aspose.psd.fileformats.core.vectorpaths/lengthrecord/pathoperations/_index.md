---
title: LengthRecord.PathOperations
second_title: Aspose.PSD untuk Referensi .NET API
description: LengthRecord Properti. Mendapat atau menyetel operasi jalur.
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/pathoperations/
---
## LengthRecord.PathOperations property

Mendapat atau menyetel operasi jalur.

```csharp
public PathOperations PathOperations { get; set; }
```

### Contoh

Contoh kode berikut menunjukkan dukungan properti LengthRecord baru, PathOperations (operasi boolean), ShapeIndex dan BezierKnotRecordsCount.

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

    // Di sini kita mengubah cara menggabungkan antara bentuk.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Lihat juga

* enum [PathOperations](../../pathoperations/)
* class [LengthRecord](../)
* ruang nama [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* perakitan [Aspose.PSD](../../../)


