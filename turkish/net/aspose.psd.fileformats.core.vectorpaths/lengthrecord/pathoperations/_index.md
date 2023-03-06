---
title: LengthRecord.PathOperations
second_title: Aspose.PSD for .NET API Referansı
description: LengthRecord mülk. Yol işlemlerini alır veya ayarlar.
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/pathoperations/
---
## LengthRecord.PathOperations property

Yol işlemlerini alır veya ayarlar.

```csharp
public PathOperations PathOperations { get; set; }
```

### Örnekler

Aşağıdaki kod örneği, yeni LengthRecord özellikleri, PathOperations (boole işlemleri), ShapeIndex ve BezierKnotRecordsCount desteğini gösterir.

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

    // Burada iki şekli birleştirmenin yolunu değiştiriyoruz.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Ayrıca bakınız

* enum [PathOperations](../../pathoperations/)
* class [LengthRecord](../)
* ad alanı [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* toplantı [Aspose.PSD](../../../)


