---
title: "Interface IVectorPathData"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData interface. L'interface pour accéder aux données du chemin vectoriel"
type: docs
weight: 1360
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
{{< psd/tize >}}
## IVectorPathData interface

L'interface d'accès aux données du chemin vectoriel.

```csharp
public interface IVectorPathData
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est désactivée. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est inversée. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance n'est pas liée. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Obtient ou définit les enregistrements de chemin. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Obtient ou définit la version. |

## Exemples

Cet exemple montre la prise en charge de la ressource 'WorkingPathResource' dans PsdImage.ImageResources pour le bon fonctionnement de l'opération de recadrage.

```csharp
[C#]

// Recadrer l'image et enregistrer.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Rechercher la ressource WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // Recadrer et enregistrer.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Charger l'image enregistrée et vérifier les modifications.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Rechercher la ressource WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


