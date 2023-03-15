---
title: Class VibAResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VibAResource classe. Ressource VibA.
type: docs
weight: 3350
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---
## VibAResource class

Ressource VibA.

```csharp
public class VibAResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [VibAResource](vibaresource/)() | Initialise une nouvelle instance du`VibAResource` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key/) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/) { get; } | Obtient la longueur de la ressource de couche en octets. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/) { get; } | Obtient la version psd. |
| [Saturation](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/) { get; set; } | Obtient ou définit la valeur de saturation |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Obtient la signature. |
| [Vibrance](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/) { get; set; } | Obtient ou définit la valeur de vibrance |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/) | La clé d'informations sur l'outil de type. |

### Exemples

L'exemple de code suivant illustre la prise en charge de la ressource VibAResource.

```csharp
[C#]

// Exemple de prise en charge de la lecture et de l'écriture de Vibration Resource lors de l'exécution.
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

### Voir également

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


