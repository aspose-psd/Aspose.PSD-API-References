---
title: "Enum PathOperations"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations enum. Les opérations pour les formes de chemin combinant des opérations booléennes"
type: docs
weight: 1400
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

Les opérations de combinaison des formes de chemin (opérations booléennes).

```csharp
public enum PathOperations
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Exclure les formes qui se chevauchent (opération XOR). |
| CombineShapes | `1` | Combiner les formes (opération OR). C'est la valeur par défaut dans Photoshop. |
| SubtractFrontShape | `2` | Soustraire la forme avant (opération NOT). |
| IntersectShapeAreas | `3` | Intersecter les zones de forme (opération AND). |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


