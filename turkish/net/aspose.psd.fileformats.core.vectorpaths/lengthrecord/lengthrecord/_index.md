---
title: "LengthRecord.LengthRecord"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LengthRecord yapıcı. LengthRecord sınıfının yeni bir örneğini başlatır"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
{{< psd/tize >}}
## LengthRecord(byte[]) {#constructor_1}

[`LengthRecord`](../) sınıfının yeni bir örneğini başlatır

```csharp
public LengthRecord(byte[] data)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | Byte[] | Kayıt verisi. |

### Ayrıca Bakınız

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

[`LengthRecord`](../) sınıfının yeni bir örneğini başlatır

```csharp
public LengthRecord()
```

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

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


