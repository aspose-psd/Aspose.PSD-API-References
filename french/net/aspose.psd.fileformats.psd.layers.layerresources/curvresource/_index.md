---
title: CurvResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Classe CurvResource. Ressource dajustement des courbes Layer 1 octet  0 si utilise des courbes 1 si utilise des pixels sur la carte si 0 alors  2 octets  court. La valeur par défaut est 1 4 octets  int. Utilisé uniquement dernier octet par bit. Le premier bit est pour 1 canal le quatrième bit pour 4 canaux par exemple 2 octets  nombre de points courts 4 octets  nombre de points  points de la courbe 2 court  première position deuxième hauteur 4 octets  mot Crv 2 octets  court par défaut est 4 pour Curves 4 octets  int. La valeur par défaut est 1 4 octets  nombre de points 4 octets  nombre de points  points de la courbe 2 court  première position deuxième hauteur 04 octets  Interlignage à plier pour quatre si 1 alors  2 octets  court. La valeur par défaut est 1 4 octets  int. Utilisé uniquement le dernier octet. Un canal est dans un bit. Le premier bit est pour 1 canal le quatrième bit pour 4 canaux par exemple 256  nombre de canaux modifiés  valeurs ordonnées du canal dans la plage 0  255 4 octets  mot Crv  2 octets  court. La valeur par défaut est 3 pour les pixels sur map 4 octets  int Nombre de canaux 2  256 octets  court 2 pour lindex de canal 256 correspond aux valeurs ordonnées du canal dans la plage 0  255
type: docs
weight: 2380
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

Classe CurvResource. Ressource d'ajustement des courbes Layer 1 octet - 0 si utilise des courbes, 1 si utilise des pixels sur la carte si 0 alors : 2 octets - court. La valeur par défaut est 1 4 octets - int. Utilisé uniquement dernier octet par bit. Le premier bit est pour 1 canal, le quatrième bit pour 4 canaux par exemple 2 octets - nombre de points courts 4 octets * nombre de points - points de la courbe 2 court : première position, deuxième hauteur 4 octets - mot "Crv" 2 octets - court par défaut est 4 pour Curves 4 octets - int. La valeur par défaut est 1 4 octets - nombre de points 4 octets * nombre de points - points de la courbe 2 court : première position, deuxième hauteur 0-4 octets - Interlignage à plier pour quatre si 1 alors : 2 octets - court. La valeur par défaut est 1 4 octets - int. Utilisé uniquement le dernier octet. Un canal est dans un bit. Le premier bit est pour 1 canal, le quatrième bit pour 4 canaux par exemple 256 * nombre de canaux modifiés - valeurs ordonnées du canal dans la plage 0 - 255 4 octets - mot "Crv " 2 octets - court. La valeur par défaut est 3 pour les pixels sur map 4 octets - int Nombre de canaux (2 + 256) octets - court 2 pour l'index de canal, 256 correspond aux valeurs ordonnées du canal dans la plage 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [CurvResource](curvresource#constructor)(byte[]) | Initialise une nouvelle instance du[`CurvResource`](../curvresource) classe. |
| [CurvResource](curvresource#constructor_1)(int) | Initialise une nouvelle instance du[`CurvResource`](../curvresource) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est un stockage de données discret. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length) { get; } | Obtient la longueur de la ressource de couche en octets. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion) { get; } | Obtient la version psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature) { get; } | Obtient la signature. |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager)() | Obtient le gestionnaire actif. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata)(int) | Obtient les données du canal. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager)() | Obtient le gestionnaire de courbes. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey) | La clé d'informations sur l'outil de type. |

### Voir également

* class [AdjustmentLayerResource](../adjustmentlayerresource)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
