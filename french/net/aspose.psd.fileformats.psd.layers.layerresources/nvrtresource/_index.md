---
title: Class NvrtResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource classe. Classe NvrtResource. Ressource du calque dajustement inversé.
type: docs
weight: 2840
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
## NvrtResource class

Classe NvrtResource. Ressource du calque d'ajustement inversé.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | Initialise une nouvelle instance du`NvrtResource` classe. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | Initialise une nouvelle instance du`NvrtResource` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/key/) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | Obtient la longueur de la ressource de couche en octets. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/psdversion/) { get; } | Obtient la version PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | La clé d'informations sur l'outil de type. |

### Exemples

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
                    // La ressource NvrtResource est prise en charge.
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### Voir également

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


