---
title: Class PhflResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource classe. Classe PhflResource. Ressource de la couche de réglage de lexposition 2 Version   3  ou   2  12 4 octets chacun pour la couleur XYZ uniquement dans la version 3 10 espace colorimétrique de 2 octets suivi dun composant de couleur 4  2 octets uniquement dans la version 2 4 Densité 1 Préserver la luminosité
type: docs
weight: 2890
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

Classe PhflResource. Ressource de la couche de réglage de l'exposition 2 Version ( = 3 ) ou ( = 2 ) 12 4 octets chacun pour la couleur XYZ (uniquement dans la version 3) 10 espace colorimétrique de 2 octets suivi d'un composant de couleur 4 * 2 octets (uniquement dans la version 2) 4 Densité 1 Préserver la luminosité

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Obtient ou définit la densité. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | Obtient la clé de ressource de couche. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Obtient la longueur de la ressource de couche en octets. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Obtient ou définit une valeur indiquant si [préserver la luminosité]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | Obtient la version psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Obtient la signature. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Obtient la version. La valeur par défaut est 2 ou 3 |

## Méthodes

| Nom | La description |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Obtient la couleur du RVB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Définit la couleur RVB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | La clé d'informations sur l'outil de type. |

### Voir également

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


