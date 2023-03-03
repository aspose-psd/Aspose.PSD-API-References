---
title: IVectorPathData.Version
second_title: Référence de l'API Aspose.PSD pour .NET
description: IVectorPathData propriété. Obtient ou définit la version.
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/
---
## IVectorPathData.Version property

Obtient ou définit la version.

```csharp
public int Version { get; set; }
```

### Valeur de la propriété

La version.

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

* interface [IVectorPathData](../)
* espace de noms [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* Assemblée [Aspose.PSD](../../../)


