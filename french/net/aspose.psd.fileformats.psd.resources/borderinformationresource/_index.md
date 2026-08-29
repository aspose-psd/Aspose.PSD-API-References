---
title: "Classe BorderInformationResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource. La ressource contenant les informations de bordure des paramètres d'impression d'image"
type: docs
weight: 4110
url: /fr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
{{< psd/tize >}}
## BorderInformationResource class

La ressource contenant les informations de bordure des paramètres d'impression d'image.

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | Obtient la taille des données de la ressource en octets. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | Obtient la version PSD minimale requise. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour que la taille soit paire (un nom nul consiste en deux octets de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtient la signature de la ressource. Doit toujours être '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtient la taille du bloc de ressource en octets, y compris ses données. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | Obtient ou définit les unités de bordure. |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | Obtient ou définit la largeur de la bordure. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Enregistre le bloc de ressource dans le flux spécifié. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valide les valeurs de la ressource. |

## Exemples

L'exemple suivant montre la prise en charge de la ressource BorderInformationResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // mettre à jour BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Voir aussi

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


