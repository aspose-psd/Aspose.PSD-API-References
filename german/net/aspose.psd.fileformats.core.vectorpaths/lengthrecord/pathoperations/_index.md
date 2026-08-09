---
title: "LengthRecord.PathOperations"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LengthRecord-Eigenschaft. Liest oder legt die Pfadoperationen fest"
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/pathoperations/
---
{{< psd/tize >}}
## LengthRecord.PathOperations property

Liest oder setzt die Pfadoperationen.

```csharp
public PathOperations PathOperations { get; set; }
```

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

* enum [PathOperations](../../pathoperations/)
* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


