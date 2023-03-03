---
title: LengthRecord.PathOperations
second_title: Referencia de API de Aspose.PSD para .NET
description: LengthRecord propiedad. Obtiene o establece las operaciones de ruta.
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/pathoperations/
---
## LengthRecord.PathOperations property

Obtiene o establece las operaciones de ruta.

```csharp
public PathOperations PathOperations { get; set; }
```

### Ejemplos

El siguiente código de ejemplo demuestra la compatibilidad con las nuevas propiedades de LengthRecord, PathOperations (operaciones booleanas), ShapeIndex y BezierKnotRecordsCount.

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

    // Aquí cambiamos la forma de combinar entre formas.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Ver también

* enum [PathOperations](../../pathoperations/)
* class [LengthRecord](../)
* espacio de nombres [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* asamblea [Aspose.PSD](../../../)


