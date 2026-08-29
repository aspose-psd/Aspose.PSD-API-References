---
title: "LengthRecord.PathOperations"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti LengthRecord. Mengambil atau mengatur operasi jalur."
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/pathoperations/
---
{{< psd/tize >}}
## LengthRecord.PathOperations property

Mendapatkan atau mengatur operasi jalur.

```csharp
public PathOperations PathOperations { get; set; }
```

## Contoh

Contoh kode berikut menunjukkan dukungan untuk properti LengthRecord baru, PathOperations (operasi boolean), ShapeIndex, dan BezierKnotRecordsCount.

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

    // Di sini kami mengubah cara menggabungkan antara bentuk.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Lihat Juga

* enum [PathOperations](../../pathoperations/)
* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


