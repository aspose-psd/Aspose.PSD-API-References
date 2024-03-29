---
title: LengthRecord.ShapeIndex
second_title: Aspose.PSD für .NET-API-Referenz
description: LengthRecord eigendom. Ruft den Index der aktuellen Pfadform in der Ebene ab oder legt ihn fest.
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/shapeindex/
---
## LengthRecord.ShapeIndex property

Ruft den Index der aktuellen Pfadform in der Ebene ab oder legt ihn fest.

```csharp
public ushort ShapeIndex { get; set; }
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

* class [LengthRecord](../)
* namensraum [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* Montage [Aspose.PSD](../../../)


