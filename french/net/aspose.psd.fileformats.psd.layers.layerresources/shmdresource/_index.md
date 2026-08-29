---
title: "Classe ShmdResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ShmdResource classe. Classe ShmdResource. Paramètres de métadonnées"
type: docs
weight: 3330
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/
---
{{< psd/tize >}}
## ShmdResource class

Classe ShmdResource. Paramètres des métadonnées

```csharp
public class ShmdResource : LayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ShmdResource](shmdresource/#constructor)() | Initialise une nouvelle instance de la classe `ShmdResource`. |
| [ShmdResource](shmdresource/#constructor_1)(byte[]) | Initialise une nouvelle instance de la classe `ShmdResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| [LayerCreatedDateTime](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/layercreateddatetime/) { get; set; } | Obtient ou définit l'heure de création du calque. Si l'heure de création du calque n'est pas spécifiée, alors retourne new DateTime(0) |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| [SubResources](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/) { get; } | Obtient les sous-ressources de la ressource shmd. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/save/)(StreamContainer, int) | Enregistre le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [SubResourceHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresourceheaderlength/) | La longueur de l'en-tête de la sous-ressource |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/typetoolkey/) | La clé d'information de l'outil de type. |

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


