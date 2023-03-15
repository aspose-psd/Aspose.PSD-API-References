---
title: Class LayerGroupInformationResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Resources.LayerGroupInformationResource classe. Ressource dinformations sur le groupe de calques
type: docs
weight: 3780
url: /fr/net/aspose.psd.fileformats.psd.resources/layergroupinformationresource/
---
## LayerGroupInformationResource class

Ressource d'informations sur le groupe de calques

```csharp
public sealed class LayerGroupInformationResource : ResourceBlock
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [LayerGroupInformationResource](layergroupinformationresource/)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/datasize/) { get; } | Obtient la taille des données de ressource en octets. |
| [Groups](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/groups/) { get; set; } | Obtient ou définit les groupes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/minimalversion/) { get; } | Obtient la version PSD minimale requise. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtient ou définit le nom de la ressource. Chaîne Pascal, rembourrée pour rendre la taille égale (un nom nul se compose de deux octets de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtient la signature de la ressource. Devrait toujours être '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtient la taille du bloc de ressources en octets, y compris ses données. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Enregistre le bloc de ressources dans le flux spécifié. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valide les valeurs des ressources. |

### Voir également

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* Assemblée [Aspose.PSD](../../)


