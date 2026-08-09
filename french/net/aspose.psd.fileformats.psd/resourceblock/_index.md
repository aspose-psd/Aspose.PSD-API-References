---
title: "Classe ResourceBlock"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.ResourceBlock. Le bloc de ressources"
type: docs
weight: 4070
url: /fr/net/aspose.psd.fileformats.psd/resourceblock/
---
{{< psd/tize >}}
## ResourceBlock class

Le bloc de ressources.

```csharp
public abstract class ResourceBlock
```

## Propriétés

| Nom | Description |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | Obtient la taille des données de la ressource en octets. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | Obtient la version PSD minimale requise. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour que la taille soit paire (un nom nul consiste en deux octets de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtient la signature de la ressource. Doit toujours être '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtient la taille du bloc de ressource en octets, y compris ses données. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Enregistre le bloc de ressource dans le flux spécifié. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valide les valeurs de la ressource. |

## Champs

| Nom | Description |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | La signature de ressource d'ImageReady. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | La signature de ressource Photoshop standard. |

## Autres membres

| Nom | Description |
| --- | --- |
| enum [ResourceBlockState](../../aspose.psd.fileformats.psd/resourceblock.resourceblockstate) | Représente l'état du bloc de ressources. |

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


