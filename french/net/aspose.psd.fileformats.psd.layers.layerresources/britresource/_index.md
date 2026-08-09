---
title: "Classe BritResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource classe. Classe BritResource. Ressource du calque d'ajustement de luminosité/contraste."
type: docs
weight: 2600
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

Classe BritResource. Ressource du calque de réglage Luminosité/Contraste

```csharp
public class BritResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BritResource](britresource/#constructor)() | Initialise une nouvelle instance de la classe `BritResource`. |
| [BritResource](britresource/#constructor_1)(byte[]) | Initialise une nouvelle instance de la classe `BritResource`. La spécification du format PSD contient la description suivante : 2 Brightness 2 Contrast 2 Mean value for brightness and contrast 1 Lab color only. Il n'est pas utilisé dans les PSD modernes (CS5 et supérieurs) où CgEd est présent. CgEd stocke les propriétés d'information. |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Initialise une nouvelle instance de la classe `BritResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Obtient ou définit la luminosité. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Obtient ou définit le contraste. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | Obtient ou définit une valeur indiquant si [lab color]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Obtient ou définit la valeur moyenne pour la luminosité et le contraste. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | La clé d'information de l'outil de type. |

### Voir aussi

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


