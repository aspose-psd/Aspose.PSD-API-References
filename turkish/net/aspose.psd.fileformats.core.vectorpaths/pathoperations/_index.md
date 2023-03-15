---
title: Enum PathOperations
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations Sıralama. Birleştiren yol şekilleri için işlemler Boole işlemleri.
type: docs
weight: 1390
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

Birleştiren yol şekilleri için işlemler (Boole işlemleri).

```csharp
public enum PathOperations
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Çakışan Şekilleri Hariç Tut (XOR işlemi). |
| CombineShapes | `1` | Şekilleri Birleştir (VEYA işlemi). Bu, Photoshop. 'deki varsayılan değerdir. |
| SubtractFrontShape | `2` | Ön Şekli Çıkar (işlem DEĞİL). |
| IntersectShapeAreas | `3` | Kesişen Şekil Alanları (VE işlemi). |

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

* ad alanı [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* toplantı [Aspose.PSD](../../)


