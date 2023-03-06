---
title: LengthRecord.ShapeIndex
second_title: Aspose.PSD voor .NET API-referentie
description: LengthRecord eigendom. Haalt de index van de huidige padvorm in laag op of stelt deze in.
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/shapeindex/
---
## LengthRecord.ShapeIndex property

Haalt de index van de huidige padvorm in laag op of stelt deze in.

```csharp
public ushort ShapeIndex { get; set; }
```

### Voorbeelden

Het volgende codevoorbeeld demonstreert de ondersteuning van nieuwe LengthRecord-eigenschappen, PathOperations (booleaanse bewerkingen), ShapeIndex en BezierKnotRecordsCount.

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

    // Hier veranderen we de manier van combineren tussen vormen.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Zie ook

* class [LengthRecord](../)
* naamruimte [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* montage [Aspose.PSD](../../../)


