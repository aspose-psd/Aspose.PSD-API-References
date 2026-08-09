---
title: "Classe PhflResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource classe. Classe PhflResource. Ressource du calque d'ajustement d'exposition 2 Version 3 ou 2 12 4 octets chacun pour la couleur XYZ uniquement dans la Version 3 10 2 octets espace couleur suivi de 4 2 octets composant couleur uniquement dans la Version 2 4 Densité 1 Préserver la luminosité"
type: docs
weight: 3240
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
{{< psd/tize >}}
## PhflResource class

Classe PhflResource. Ressource du calque de réglage d’exposition Version 2 ( = 3 ) ou ( = 2 ) 12 4 octets chacun pour la couleur XYZ (uniquement dans la version 3) 10 2 octets espace colorimétrique suivi de 4 * 2 octets composante couleur (uniquement dans la version 2) 4 Densité 1 Préserver la luminosité

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Obtient ou définit la densité. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Obtient ou définit une valeur indiquant si [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Obtient la version. La valeur par défaut est 2 ou 3. |

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Obtient la couleur du RVB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Définit la couleur RVB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | La clé d'information de l'outil de type. |

### Voir aussi

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


