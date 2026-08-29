---
title: "Classe LevlResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource classe. Classe LevlResource. Ressource du calque d'ajustement d'exposition."
type: docs
weight: 2950
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

Classe LevlResource. Ressource du calque d'ajustement d'exposition

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Initialise une nouvelle instance de la classe `LevlResource`. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Initialise une nouvelle instance de la classe `LevlResource`. Pris en charge dans les modes de couleur GrayScale, Duotone, RGB, CMYK, Lab 2 octets - Version (=2) 29 * 10 octets - Jeux d’enregistrements de niveaux avec 5 entiers courts 4 octets - En-tête Lvls (commence à l'index 292) 2 octets - Version (=3) 2 octets - Nombre total d’enregistrements de niveau 10 * (Total Count - 29) La terminaison zéro de la ressource Lvls doit également être pliée pour quatre. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Obtient la version. La valeur par défaut est 2. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Obtient le canal. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | La clé d'information de l'outil de type. |

### Voir aussi

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


