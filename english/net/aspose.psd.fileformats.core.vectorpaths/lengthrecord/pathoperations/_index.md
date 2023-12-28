---
title: LengthRecord.PathOperations
second_title: Aspose.PSD for .NET API Reference
description: LengthRecord property. Gets or sets the path operations
type: docs
weight: 50
url: /net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/pathoperations/
---
{{< psd/tize >}}
## LengthRecord.PathOperations property

Gets or sets the path operations.

```csharp
public PathOperations PathOperations { get; set; }
```

## Examples

The following code example demonstrates the support of new LengthRecord properties, PathOperations (boolean operations), ShapeIndex and BezierKnotRecordsCount.

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

    // Here we changin the way to combining betwen shapes.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### See Also

* enum [PathOperations](../../pathoperations/)
* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* assembly [Aspose.PSD](../../../)


