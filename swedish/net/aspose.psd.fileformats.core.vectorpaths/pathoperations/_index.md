---
title: Enum PathOperations
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations uppräkning. Operationerna för kombinationen av banformerna booleska operationer.
type: docs
weight: 1390
url: /sv/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

Operationerna för kombinationen av banformerna (booleska operationer).

```csharp
public enum PathOperations
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Exkludera överlappande former (XOR-operation). |
| CombineShapes | `1` | Kombinera former (ELLER-operation). Detta är standardvärdet i Photoshop. |
| SubtractFrontShape | `2` | Subtrahera frontform (INTE operation). |
| IntersectShapeAreas | `3` | Skär formområden (OCH operation). |

### Exempel

Följande kodexempel visar stöd för nya LengthRecord-egenskaper, PathOperations (booleska operationer), ShapeIndex och BezierKnotRecordsCount.

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

* namnutrymme [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* hopsättning [Aspose.PSD](../../)


