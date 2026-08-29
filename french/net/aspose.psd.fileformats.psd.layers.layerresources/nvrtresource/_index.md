---
title: "Classe NvrtResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource. Classe NvrtResource. Ressource du calque d'ajustement Invert."
type: docs
weight: 3180
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
{{< psd/tize >}}
## NvrtResource class

Classe NvrtResource. Ressource du calque de réglage d’inversion.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | Initialise une nouvelle instance de la classe `NvrtResource`. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | Initialise une nouvelle instance de la classe `NvrtResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

L'exemple suivant montre comment obtenir NvrtResource.

```csharp
[C#]

string sourceFilePath = "InvertAdjustmentLayer.psd";
NvrtResource resource = null;
using (PsdImage psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    foreach (Aspose.PSD.FileFormats.Psd.Layers.Layer layer in psdImage.Layers)
    {
        if (layer is InvertAdjustmentLayer)
        {
            foreach (Aspose.PSD.FileFormats.Psd.Layers.LayerResource layerResource in layer.Resources)
            {
                if (layerResource is NvrtResource)
                {
                    // Le NvrtResource est pris en charge.
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### Voir aussi

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


