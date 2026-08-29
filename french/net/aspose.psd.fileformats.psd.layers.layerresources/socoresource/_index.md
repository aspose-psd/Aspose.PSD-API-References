---
title: "Classe SoCoResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource. Classe SoCoResource. Cette ressource contient des informations sur les calques de remplissage de couleur"
type: docs
weight: 3360
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
{{< psd/tize >}}
## SoCoResource class

Classe SoCoResource. Cette ressource contient des informations sur les calques de remplissage de couleur.

```csharp
public class SoCoResource : FillLayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SoCoResource](socoresource/)() | Initialise une nouvelle instance de la classe `SoCoResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | Obtient la couleur RVB. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

L'exemple suivant montre comment modifier SoCoResource (Ressource de calque pour le calque de remplissage de couleur)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Chargez une image existante dans une instance de la classe PsdImage
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Recherche de FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Recherche de SoCoResource dans la liste des ressources de calque
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // Définition de la propriété Color de SoCoResource
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


