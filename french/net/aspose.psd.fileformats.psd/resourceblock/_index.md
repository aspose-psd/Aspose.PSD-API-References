---
title: Class ResourceBlock
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.ResourceBlock classe. Le bloc de ressources.
type: docs
weight: 3610
url: /fr/net/aspose.psd.fileformats.psd/resourceblock/
---
## ResourceBlock class

Le bloc de ressources.

```csharp
public abstract class ResourceBlock
```

## Propriétés

| Nom | La description |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | Obtient la taille des données de ressource en octets. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | Obtient la version PSD minimale requise. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtient ou définit le nom de la ressource. Chaîne Pascal, rembourrée pour rendre la taille égale (un nom nul se compose de deux octets de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtient la signature de la ressource. Devrait toujours être '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtient la taille du bloc de ressources en octets, y compris ses données. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Enregistre le bloc de ressources dans le flux spécifié. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valide les valeurs des ressources. |

## Des champs

| Nom | La description |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | La signature de ressource de ImageReady. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | La signature de ressource Photoshop habituelle. |

## Autres membres

| Nom | La description |
| --- | --- |
| enum [ResourceBlockState](resourceblock.resourceblockstate/) | Représente l'état du bloc de ressources. |

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* Assemblée [Aspose.PSD](../../)


