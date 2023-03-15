---
title: Class MixrResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource classe. Classe MixrResource. Ressource de Channel Mixer Adjustment Layer
type: docs
weight: 2820
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Classe MixrResource. Ressource de Channel Mixer Adjustment Layer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Initialise une nouvelle instance du`MixrResource` class. La spécification du format PSD contient la description suivante : 2 Version ( = 1) 2 Monochrome 20 Couleur RVB ou CMJN plus constante pour les paramètres du mélangeur. 4 * 2 octets de couleur avec 2 octets de constant. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Initialise une nouvelle instance du`MixrResource` class. La spécification du format PSD contient la description suivante : 2 Version ( = 1) 2 Monochrome 20 Couleur RVB ou CMJN plus constante pour les paramètres du mélangeur. 4 * 2 octets de couleur avec 2 octets de constant. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Obtient la longueur de la ressource de couche en octets. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Obtient ou définit une valeur indiquant si cette`MixrResource` est monochrome. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | Obtient la version psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Obtient la signature. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Obtient ou définit la version. |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Obtient les informations brutes du canal data |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Définit les informations du canal. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | La clé d'informations sur l'outil de type. |

### Voir également

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


