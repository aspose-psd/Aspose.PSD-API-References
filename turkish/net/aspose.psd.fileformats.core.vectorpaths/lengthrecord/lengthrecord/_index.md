---
title: LengthRecord.LengthRecord
second_title: Aspose.PSD for .NET API Referansı
description: LengthRecord inşaatçı. Yeni bir örneğini başlatır.LengthRecord sınıf.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
## LengthRecord(byte[]) {#constructor_1}

Yeni bir örneğini başlatır.[`LengthRecord`](../) sınıf.

```csharp
public LengthRecord(byte[] data)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| data | Byte[] | Kayıt verileri. |

### istisnalar

| istisna | şart |
| --- | --- |
| !:PsdImageArgumentException | Uzunluk Kaydı oluşturma için yanlış veriler |

### Ayrıca bakınız

* class [LengthRecord](../)
* ad alanı [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* toplantı [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

Yeni bir örneğini başlatır.[`LengthRecord`](../) sınıf.

```csharp
public LengthRecord()
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

* class [LengthRecord](../)
* ad alanı [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* toplantı [Aspose.PSD](../../../)


