---
title: Class VogkResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VogkResource classe. La ressource de données dorigine vectorielle.
type: docs
weight: 3370
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---
## VogkResource class

La ressource de données d'origine vectorielle.

```csharp
public sealed class VogkResource : LayerResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [VogkResource](vogkresource/)() | Initialise une nouvelle instance du`VogkResource` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key/) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/) { get; } | Obtient la longueur de la ressource de couche en octets. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/) { get; } | Obtient la version minimale de psd requise pour la ressource de couche. 0 indique aucune restriction. |
| [ShapeOriginSettings](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings/) { get; set; } | Obtient ou définit les paramètres d'origine de la forme. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/signature/) { get; } | Obtient la signature de ressource de couche. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/version/) { get; set; } | Obtient ou définit la version. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/typetoolkey/) | La clé d'informations sur l'outil de type. |

### Exemples

L'exemple suivant illustre la prise en charge de la ressource VogkResource.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // En lisant
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Édition
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Voir également

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


