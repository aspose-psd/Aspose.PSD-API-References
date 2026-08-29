---
title: "Enum PathOperations"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations enum. Operasi untuk bentuk jalur yang menggabungkan operasi Boolean"
type: docs
weight: 1400
url: /id/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

Operasi untuk menggabungkan bentuk jalur (operasi Boolean).

```csharp
public enum PathOperations
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Kecualikan Bentuk yang Tumpang Tindih (operasi XOR). |
| CombineShapes | `1` | Gabungkan Bentuk (operasi OR). Ini adalah nilai default di Photoshop. |
| SubtractFrontShape | `2` | Kurangi Bentuk Depan (operasi NOT). |
| IntersectShapeAreas | `3` | Interseksi Area Bentuk (operasi AND). |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


