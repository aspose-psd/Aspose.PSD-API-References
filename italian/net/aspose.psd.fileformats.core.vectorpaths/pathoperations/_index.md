---
title: Enum PathOperations
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations enum. Le operazioni per la combinazione delle forme del percorso operazioni booleane.
type: docs
weight: 1390
url: /it/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

Le operazioni per la combinazione delle forme del percorso (operazioni booleane).

```csharp
public enum PathOperations
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Escludi forme sovrapposte (operazione XOR). |
| CombineShapes | `1` | Combina forme (operazione OR). Questo è il valore predefinito in Photoshop. |
| SubtractFrontShape | `2` | Sottrai forma frontale (NON operazione). |
| IntersectShapeAreas | `3` | Interseca le aree della forma (operazione AND). |

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

* spazio dei nomi [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assemblea [Aspose.PSD](../../)


