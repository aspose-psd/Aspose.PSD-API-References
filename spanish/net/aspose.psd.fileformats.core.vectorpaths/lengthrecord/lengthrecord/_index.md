---
title: "LengthRecord.LengthRecord"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "LengthRecord constructor. Inicializa una nueva instancia de la clase LengthRecord"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
{{< psd/tize >}}
## LengthRecord(byte[]) {#constructor_1}

Inicializa una nueva instancia de la clase [`LengthRecord`](../).

```csharp
public LengthRecord(byte[] data)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | Byte[] | Los datos del registro. |

### Ver también

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

Inicializa una nueva instancia de la clase [`LengthRecord`](../).

```csharp
public LengthRecord()
```

## Ejemplos

El siguiente ejemplo de código demuestra el soporte de nuevas propiedades LengthRecord, PathOperations (operaciones booleanas), ShapeIndex y BezierKnotRecordsCount.

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

    // Aquí cambiamos la forma de combinar entre shapes.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Ver también

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


