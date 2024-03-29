---
title: Enum PathOperations
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations opsomming. Die Operationen zum Kombinieren der Pfadformen boolesche Operationen.
type: docs
weight: 1390
url: /de/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

Die Operationen zum Kombinieren der Pfadformen (boolesche Operationen).

```csharp
public enum PathOperations
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Überlappende Formen ausschließen (XOR-Operation). |
| CombineShapes | `1` | Formen kombinieren (ODER-Verknüpfung). Dies ist der Standardwert in Photoshop. |
| SubtractFrontShape | `2` | Vordere Form subtrahieren (KEINE Operation). |
| IntersectShapeAreas | `3` | Formbereiche überschneiden (UND-Verknüpfung). |

### Beispiele

Das folgende Codebeispiel veranschaulicht die Unterstützung der neuen LengthRecord-Eigenschaften PathOperations (boolesche Operationen), ShapeIndex und BezierKnotRecordsCount.

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

    // Hier ändern wir den Weg zum Kombinieren zwischen Formen.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* Montage [Aspose.PSD](../../)


