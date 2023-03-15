---
title: Enum PathOperations
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations énumération. Les opérations de combinaison des formes de chemin opérations booléennes.
type: docs
weight: 1390
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

Les opérations de combinaison des formes de chemin (opérations booléennes).

```csharp
public enum PathOperations
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Exclure les formes qui se chevauchent (opération XOR). |
| CombineShapes | `1` | Combiner les formes (opération OU). C'est la valeur par défaut dans Photoshop. |
| SubtractFrontShape | `2` | Soustraire la forme avant (PAS opération). |
| IntersectShapeAreas | `3` | Intersection des zones de forme (opération ET). |

### Exemples

L'exemple de code suivant illustre la prise en charge des nouvelles propriétés LengthRecord, PathOperations (opérations booléennes), ShapeIndex et BezierKnotRecordsCount.

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

    // Ici, nous changeons la façon de combiner entre les formes.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* Assemblée [Aspose.PSD](../../)


