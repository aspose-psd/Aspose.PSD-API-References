---
title: "LengthRecord.ShapeIndex"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "LengthRecord propriété. Obtient ou définit l'index de la forme de chemin actuelle dans le calque"
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/shapeindex/
---
{{< psd/tize >}}
## LengthRecord.ShapeIndex property

Obtient ou définit l'index de la forme de chemin actuelle dans le calque.

```csharp
public ushort ShapeIndex { get; set; }
```

## Exemples

L'exemple de code suivant démontre la prise en charge des nouvelles propriétés LengthRecord, PathOperations (opérations booléennes), ShapeIndex et BezierKnotRecordsCount.

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

    // Ici nous modifions la façon de combiner les formes.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Voir aussi

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


