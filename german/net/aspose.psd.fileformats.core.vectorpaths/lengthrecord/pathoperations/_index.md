---
title: LengthRecord.PathOperations
second_title: Aspose.PSD für .NET-API-Referenz
description: LengthRecord eigendom. Ruft die Pfadoperationen ab oder legt sie fest.
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/pathoperations/
---
## LengthRecord.PathOperations property

Ruft die Pfadoperationen ab oder legt sie fest.

```csharp
public PathOperations PathOperations { get; set; }
```

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

* enum [PathOperations](../../pathoperations/)
* class [LengthRecord](../)
* namensraum [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* Montage [Aspose.PSD](../../../)


