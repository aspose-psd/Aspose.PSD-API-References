---
title: "Enumeración PathOperations"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Enumeración Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations. Las operaciones para las formas de ruta que combinan operaciones booleanas."
type: docs
weight: 1400
url: /es/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

Las operaciones para combinar formas de ruta (operaciones booleanas).

```csharp
public enum PathOperations
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Excluir formas superpuestas (operación XOR). |
| CombineShapes | `1` | Combinar formas (operación OR). Este es el valor predeterminado en Photoshop. |
| SubtractFrontShape | `2` | Restar forma frontal (operación NOT). |
| IntersectShapeAreas | `3` | Intersectar áreas de forma (operación AND). |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


