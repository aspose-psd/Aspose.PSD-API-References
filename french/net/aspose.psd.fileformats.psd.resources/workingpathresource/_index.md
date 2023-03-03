---
title: Class WorkingPathResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource classe. Ressource de chemin de travail.
type: docs
weight: 3980
url: /fr/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
## WorkingPathResource class

Ressource de chemin de travail.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | Initialise une nouvelle instance du`WorkingPathResource` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | Obtient la taille des données de ressource en octets. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est désactivée. |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est inversée. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance n'est pas liée. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | Obtient la version PSD minimale requise. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtient ou définit le nom de la ressource. Chaîne Pascal, rembourrée pour rendre la taille égale (un nom nul se compose de deux octets de 0). |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | Obtient ou définit les enregistrements de chemin. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtient la signature de la ressource. Devrait toujours être '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtient la taille du bloc de ressources en octets, y compris ses données. |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | Obtient ou définit la version. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Enregistre le bloc de ressources dans le flux spécifié. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valide les valeurs des ressources. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* Assemblée [Aspose.PSD](../../)


