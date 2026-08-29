---
title: "Classe VibAResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VibAResource. Ressource VibA"
type: docs
weight: 3750
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---
{{< psd/tize >}}
## VibAResource class

Ressource VibA.

```csharp
public class VibAResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VibAResource](vibaresource/)() | Initialise une nouvelle instance de la classe `VibAResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| [Saturation](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/) { get; set; } | Obtient ou définit la valeur de saturation |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| [Vibrance](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/) { get; set; } | Obtient ou définit la valeur de vibrance |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

L'exemple de code suivant montre la prise en charge de la ressource VibAResource.

```csharp
[C#]

// Exemple de prise en charge de la lecture et de l'écriture de la ressource Vibration à l'exécution.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### Voir aussi

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


