---
title: "Classe PhflResourceVersion2"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 class. Classe PhflResource. Ressource du calque d'ajustement d'exposition 2 Version   3  ou   2  12 4 octets chacun pour la couleur XYZ uniquement dans la Version 3 10 2 octets d'espace couleur suivis de 4  2 octets de composant couleur uniquement dans la Version 2 4 Densité 1 Préserver la luminosité"
type: docs
weight: 3250
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
{{< psd/tize >}}
## PhflResourceVersion2 class

Classe PhflResource. Ressource du calque de réglage d’exposition Version 2 ( = 3 ) ou ( = 2 ) 12 4 octets chacun pour la couleur XYZ (uniquement dans la version 3) 10 2 octets espace colorimétrique suivi de 4 * 2 octets composante couleur (uniquement dans la version 2) 4 Densité 1 Préserver la luminosité

```csharp
public class PhflResourceVersion2 : PhflResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | Initialise une nouvelle instance de la classe `PhflResourceVersion2`. |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | Initialise une nouvelle instance de la classe `PhflResourceVersion2`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | Obtient l'espace colorimétrique. |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | Obtient ou définit le composant A de la couleur |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | Obtient ou définit le composant B |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | Obtient ou définit le composant L de la couleur |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Obtient ou définit la densité. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Obtient ou définit une valeur indiquant si [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | Obtient la version. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | Obtient la couleur. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | Définit la couleur RVB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

### Voir aussi

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


