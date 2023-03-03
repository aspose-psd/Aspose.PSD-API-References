---
title: LengthRecord.ShapeIndex
second_title: Aspose.PSD per riferimento API .NET
description: LengthRecord proprietà. Ottiene o imposta lindice della forma del percorso corrente nel livello.
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/shapeindex/
---
## LengthRecord.ShapeIndex property

Ottiene o imposta l'indice della forma del percorso corrente nel livello.

```csharp
public ushort ShapeIndex { get; set; }
```

### Esempi

L'esempio di codice seguente illustra il supporto delle nuove proprietà LengthRecord, PathOperations (operazioni booleane), ShapeIndex e BezierKnotRecordsCount.

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

    // Qui cambiamo il modo di combinare le forme.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Guarda anche

* class [LengthRecord](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* assemblea [Aspose.PSD](../../../)


