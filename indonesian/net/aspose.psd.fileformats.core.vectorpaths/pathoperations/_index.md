---
title: Enum PathOperations
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations enum. Operasi untuk penggabungan bentuk jalur operasi Boolean.
type: docs
weight: 1390
url: /id/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

Operasi untuk penggabungan bentuk jalur (operasi Boolean).

```csharp
public enum PathOperations
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Kecualikan Bentuk Tumpang Tindih (operasi XOR). |
| CombineShapes | `1` | Gabungkan Bentuk (Operasi ATAU). Ini adalah nilai default di Photoshop. |
| SubtractFrontShape | `2` | Kurangi Bentuk Depan (BUKAN operasi). |
| IntersectShapeAreas | `3` | Bidang Bentuk Perpotongan (Operasi AND). |

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

* ruang nama [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* perakitan [Aspose.PSD](../../)


