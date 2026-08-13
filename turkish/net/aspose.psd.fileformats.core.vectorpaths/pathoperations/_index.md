---
title: "Enum PathOperations"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations enum. Yol şekillerini birleştiren Boolean işlemleri için operasyonlar"
type: docs
weight: 1400
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

Yol şekillerinin birleştirilmesi (Boolean işlemler) için işlemler.

```csharp
public enum PathOperations
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Üst üste gelen şekilleri dışla (XOR işlemi). |
| CombineShapes | `1` | Şekilleri birleştir (OR işlemi). Bu, Photoshop'ta varsayılan değerdir. |
| SubtractFrontShape | `2` | Ön şekli çıkar (NOT işlemi). |
| IntersectShapeAreas | `3` | Şekil alanlarını kesiştir (AND işlemi). |

## Örnekler

Aşağıdaki kod örneği, yeni LengthRecord özellikleri, PathOperations (boolean işlemler), ShapeIndex ve BezierKnotRecordsCount desteğini gösterir.

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

    // Burada şekiller arasındaki birleştirme yöntemini değiştiriyoruz.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


