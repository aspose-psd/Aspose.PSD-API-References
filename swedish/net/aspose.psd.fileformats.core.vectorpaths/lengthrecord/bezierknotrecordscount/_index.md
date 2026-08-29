---
title: "LengthRecord.BezierKnotRecordsCount"
second_title: "Aspose.PSD för .NET API‑referens"
description: "LengthRecord egenskap. Hämtar eller anger antalet Bezier-knutregister"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/bezierknotrecordscount/
---
{{< psd/tize >}}
## LengthRecord.BezierKnotRecordsCount property

Hämtar eller anger antalet bezier knot-poster.

```csharp
public int BezierKnotRecordsCount { get; set; }
```

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

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


