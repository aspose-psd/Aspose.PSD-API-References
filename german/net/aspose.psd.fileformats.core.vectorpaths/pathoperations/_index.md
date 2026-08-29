---
title: "Aufzählung PathOperations"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations enum. Die Operationen für die Pfadformen, die Boolesche Operationen kombinieren"
type: docs
weight: 1400
url: /de/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

Die Vorgänge zum Kombinieren von Pfadformen (Boolesche Operationen).

```csharp
public enum PathOperations
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Überschneidende Formen ausschließen (XOR-Operation). |
| CombineShapes | `1` | Formen kombinieren (OR-Operation). Dies ist der Standardwert in Photoshop. |
| SubtractFrontShape | `2` | Vordere Form subtrahieren (NOT-Operation). |
| IntersectShapeAreas | `3` | Formflächen schneiden (AND-Operation). |

## Beispiele

Das folgende Codebeispiel demonstriert die Unterstützung neuer LengthRecord‑Eigenschaften, PathOperations (boolesche Operationen), ShapeIndex und BezierKnotRecordsCount.

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

    // Hier ändern wir die Art und Weise, Formen zu kombinieren.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


