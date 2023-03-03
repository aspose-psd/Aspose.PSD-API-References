---
title: Interface IVectorPathData
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData interface. Linterface daccès aux données de chemin vectoriel.
type: docs
weight: 1350
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

L'interface d'accès aux données de chemin vectoriel.

```csharp
public interface IVectorPathData
```

## Propriétés

| Nom | La description |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est désactivée. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est inversée. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance n'est pas liée. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Obtient ou définit les enregistrements de chemin. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Obtient ou définit la version. |

### Exemples

Cet exemple illustre la prise en charge de la ressource 'WorkingPathResource' dans PsdImage.ImageResources pour le bon fonctionnement de l'opération Crop.

```csharp
[C#]

// Rogner l'image et enregistrer.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Recherche la ressource WorkingPathResource.
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

    // Rogner et enregistrer.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Charge l'image enregistrée et vérifie les modifications.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Recherche la ressource WorkingPathResource.
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

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* Assemblée [Aspose.PSD](../../)


