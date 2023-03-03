---
title: Class TransparencyIndexResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Resources.TransparencyIndexResource classe. Le bloc de ressources dindex de transparence.
type: docs
weight: 3920
url: /fr/net/aspose.psd.fileformats.psd.resources/transparencyindexresource/
---
## TransparencyIndexResource class

Le bloc de ressources d'index de transparence.

```csharp
public sealed class TransparencyIndexResource : ResourceBlock
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TransparencyIndexResource](transparencyindexresource/)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/datasize/) { get; } | Obtient la taille des données de ressource en octets. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/minimalversion/) { get; } | Obtient la version psd minimale requise. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtient ou définit le nom de la ressource. Chaîne Pascal, rembourrée pour rendre la taille égale (un nom nul se compose de deux octets de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtient la signature de la ressource. Devrait toujours être '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtient la taille du bloc de ressources en octets, y compris ses données. |
| [TransparencyIndex](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/transparencyindex/) { get; set; } | Obtient ou définit l'index de couleur de transparence. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Enregistre le bloc de ressources dans le flux spécifié. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valide les valeurs des ressources. |

### Voir également

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* Assemblée [Aspose.PSD](../../)


