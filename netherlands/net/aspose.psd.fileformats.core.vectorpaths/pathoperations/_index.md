---
title: Enum PathOperations
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations opsomming. De bewerkingen voor het combineren van padvormen Booleaanse bewerkingen.
type: docs
weight: 1390
url: /nl/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

De bewerkingen voor het combineren van padvormen (Booleaanse bewerkingen).

```csharp
public enum PathOperations
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Overlappende vormen uitsluiten (XOR-bewerking). |
| CombineShapes | `1` | Vormen combineren (OF-bewerking). Dit is de standaardwaarde in Photoshop. |
| SubtractFrontShape | `2` | Frontvorm aftrekken (GEEN bewerking). |
| IntersectShapeAreas | `3` | Vormgebieden doorsnijden (AND-bewerking). |

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

* naamruimte [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* montage [Aspose.PSD](../../)


