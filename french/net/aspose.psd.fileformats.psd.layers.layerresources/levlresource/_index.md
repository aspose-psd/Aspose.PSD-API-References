---
title: Class LevlResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource classe. Classe LevlResource. Ressource de la couche de réglage de lexposition
type: docs
weight: 2640
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
## LevlResource class

Classe LevlResource. Ressource de la couche de réglage de l'exposition

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Initialise une nouvelle instance du`LevlResource` classe. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Initialise une nouvelle instance du`LevlResource` class. Pris en charge dans les modes de couleur GrayScale, Duotone, RVB, CMJN, Lab 2 octets - Version (=2) 29 * 10 octets - Ensembles d'enregistrements de niveau avec 5 entiers courts 4 octets - En-tête Lvls (commence à l'index 292) 2 octets - Version (=3) 2 octets - Nombre total d'enregistrements de niveau 10 * (Nombre total - 29) La fin zéro de la ressource Lvls doit également être pliée pour quatre |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/key/) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Obtient la longueur de la ressource de couche en octets. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/psdversion/) { get; } | Obtient la version psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Obtient la signature. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Obtient la version. La valeur par défaut est 2 |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Obtient la chaîne. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | La clé d'informations sur l'outil de type. |

### Voir également

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


