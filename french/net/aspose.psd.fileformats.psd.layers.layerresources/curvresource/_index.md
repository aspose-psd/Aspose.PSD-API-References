---
title: "Classe CurvResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource classe. Classe CurvResource. Ressource du calque d'ajustement de courbes 1 byte  0 si utilisation de courbes 1 si pixels utilisés sur la carte si 0 alors 2 bytes  short. Valeur par défaut : 1 4 bytes  int. Utilisé uniquement le dernier octet par bit. Le premier bit est pour 1 canal, le quatrième bit pour 4 canaux, par exemple 2 bytes  short nombre de points 4 bytes  nombre de points  points de la courbe 2 short première position seconde hauteur 4 bytes  word Crv  2 bytes  short valeur par défaut : 4 pour les courbes 4 bytes  int. Valeur par défaut : 1 4 bytes  nombre de points 4 bytes  nombre de points  points de la courbe 2 short première position seconde hauteur 04 bytes  Conduisant à être plié pour quatre si 1 alors 2 bytes  short. Valeur par défaut : 1 4 bytes  int. Utilisé uniquement le dernier octet. Un canal est dans un bit. Le premier bit est pour 1 canal, le quatrième bit pour 4 canaux, par exemple 256  nombre de canaux modifiés  valeurs ordonnées du canal dans la plage 0 – 255 4 bytes  word Crv  2 bytes  short. Valeur par défaut : 3 pour les pixels sur la carte 4 bytes  int Nombre de canaux 2  256 bytes  short 2 pour l'index du canal 256 est valeurs ordonnées du canal dans la plage 0 – 255"
type: docs
weight: 2660
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

Classe CurvResource. Ressource du calque de réglage Courbes 1 octet - 0 si utilisation des courbes, 1 si utilisation des pixels sur la carte ; si 0 alors : 2 octets - short. Valeur par défaut 1. 4 octets - int. Utilisé uniquement le dernier octet par bit. Le premier bit correspond à 1 canal, le quatrième bit à 4 canaux, par exemple 2 octets - short nombre de points. 4 octets * nombre de points - points de la courbe. 2 short : première position, deuxième hauteur. 4 octets - mot "Crv ". 2 octets - short valeur par défaut 4 pour les Courbes. 4 octets - int. Valeur par défaut 1. 4 octets - nombre de points. 4 octets * nombre de points - points de la courbe. 2 short : première position, deuxième hauteur. 0-4 octets - En-tête pour être plié pour quatre si 1 alors : 2 octets - short. Valeur par défaut 1. 4 octets - int. Utilisé uniquement le dernier octet. Un canal est dans un bit. Le premier bit pour 1 canal, le quatrième bit pour 4 canaux, par exemple 256 * nombre de canaux modifiés - valeurs ordonnées du canal dans la plage 0 - 255 4 octets - mot "Crv " 2 octets - short. Valeur par défaut 3 pour les pixels sur la carte 4 octets - int Nombre de canaux (2 + 256) octets - short 2 pour l'index du canal, 256 sont les valeurs ordonnées du canal dans la plage 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Initialise une nouvelle instance de la classe `CurvResource`. |
| [CurvResource](curvresource/#constructor_1)(int) | Initialise une nouvelle instance de la classe `CurvResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est stockée de manière discrète. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Obtient le gestionnaire actif. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Obtient les données du canal. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Obtient le gestionnaire de courbe. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | La clé d'information de l'outil de type. |

### Voir aussi

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


