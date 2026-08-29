---
title: "Enum PathOperations"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations‑enum. Operationerna för banformer som kombinerar booleska operationer"
type: docs
weight: 1400
url: /sv/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

Operationerna för kombination av vägformer (Boolean-operationer).

```csharp
public enum PathOperations
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Exkludera överlappande former (XOR‑operation). |
| CombineShapes | `1` | Kombinera former (OR‑operation). Detta är standardvärdet i Photoshop. |
| SubtractFrontShape | `2` | Subtrahera frontformen (NOT‑operation). |
| IntersectShapeAreas | `3` | Korsa formytor (AND‑operation). |

## Exempel

Följande kodexempel demonstrerar stödet för nya LengthRecord‑egenskaper, PathOperations (boolska operationer), ShapeIndex och BezierKnotRecordsCount.

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

    // Här ändrar vi sättet att kombinera mellan former.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Se även

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


