---
title: "Classe MixrResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource. Classe MixrResource. Ressource du calque d'ajustement du mélangeur de canaux"
type: docs
weight: 3160
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

Classe MixrResource. Ressource du calque de réglage du mélangeur de canaux

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Initialise une nouvelle instance de la classe `MixrResource`. La spécification du format PSD contient la description suivante : 2 Version (= 1) 2 Monochrome 20 couleur RVB ou CMJN plus constante pour les réglages du mélangeur. 4 * 2 octets de couleur avec 2 octets de constante. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Initialise une nouvelle instance de la classe `MixrResource`. La spécification du format PSD contient la description suivante : 2 Version (= 1) 2 Monochrome 20 couleur RVB ou CMJN plus constante pour les réglages du mélangeur. 4 * 2 octets de couleur avec 2 octets de constante. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Obtient ou définit une valeur indiquant si ce `MixrResource` est monochrome. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Obtient ou définit la version. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Obtient les données brutes des informations du canal |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Définit les informations du canal. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | La clé d'information de l'outil de type. |

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


