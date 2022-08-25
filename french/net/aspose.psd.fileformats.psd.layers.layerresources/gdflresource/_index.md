---
title: GdFlResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Classe GdFlResource. Cette ressource contient des informations sur le mélange déléments tronqués.
type: docs
weight: 2480
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---
## GdFlResource class

Classe GdFlResource. Cette ressource contient des informations sur le mélange d'éléments tronqués.

```csharp
public class GdFlResource : FillLayerResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [GdFlResource](gdflresource)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/alignwithlayer) { get; set; } | Obtient ou définit une valeur indiquant si [aligner avec le calque]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/angle) { get; set; } | Obtient ou définit l'angle. |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/color) { get; set; } | Obtient la couleur du RVB. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/colorpoints) { get; set; } | Obtient les points de couleur. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/dither) { get; set; } | Obtient ou définit une valeur indiquant si cette[`GdFlResource`](../gdflresource) est le tramage. |
| [GradientInterval](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientinterval) { get; set; } | Obtient ou définit l'intervalle de gradient. |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientname) { get; set; } | Obtient ou définit le nom du dégradé. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradienttype) { get; set; } | Obtient ou définit le type de dégradé. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/horizontaloffset) { get; set; } | Obtient ou définit le décalage horizontal. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/key) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/length) { get; } | Obtient la longueur de la ressource de couche en octets. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/psdversion) { get; } | Obtient la version minimale de psd requise pour la ressource de couche. 0 indique aucune restriction. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/reverse) { get; set; } | Obtient ou définit une valeur indiquant si cette[`GdFlResource`](../gdflresource) est inversé. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/scale) { get; set; } | Obtient ou définit l'échelle. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/signature) { get; } | Obtient la signature de ressource de couche. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/transparencypoints) { get; set; } | Obtient les points de transparence. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/verticaloffset) { get; set; } | Obtient ou définit le décalage vertical. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/save)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/typetoolkey) | La clé d'informations sur l'outil de type. |

### Exemples

L'exemple suivant illustre la prise en charge du chargement des ressources GdFlResource.

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string exportPath = "ComplexGradientFillLayer_after.psd";
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is GdFlResource)
                {
                    // En lisant
                    var resource = (GdFlResource)res;
                    if (resource.AlignWithLayer != false ||
                     (Math.Abs(resource.Angle - 45.0) > 0.001) ||
                     resource.Dither != true ||
                     resource.Reverse != false ||
                     resource.Color != Color.Empty ||
                     Math.Abs(resource.HorizontalOffset - (-39)) > 0.001 ||
                     Math.Abs(resource.VerticalOffset - (-5)) > 0.001 ||
                     resource.TransparencyPoints.Length != 3 ||
                     resource.ColorPoints.Length != 2)
                    {
                        throw new Exception("Resource Parameters were read wrong");
                    }
                    var transparencyPoints = resource.TransparencyPoints;
                    if (Math.Abs(100.0 - transparencyPoints[0].Opacity) > 0.25 ||
                     transparencyPoints[0].Location != 0 ||
                     transparencyPoints[0].MedianPointLocation != 50 ||
                     Math.Abs(50.0 - transparencyPoints[1].Opacity) > 0.25 ||
                     transparencyPoints[1].Location != 2048 ||
                     transparencyPoints[1].MedianPointLocation != 50 ||
                     Math.Abs(100.0 - transparencyPoints[2].Opacity) > 0.25 ||
                     transparencyPoints[2].Location != 4096 ||
                     transparencyPoints[2].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Transparency Points were read Wrong");
                    }
                    var colorPoints = resource.ColorPoints;
                    if (colorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
                     colorPoints[0].Location != 0 ||
                     colorPoints[0].MedianPointLocation != 50 ||
                     colorPoints[1].Color != Color.FromArgb(203, 0, 0) ||
                     colorPoints[1].Location != 4096 ||
                     colorPoints[1].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Color Points were read Wrong");
                    }
                    // Édition
                    resource.Angle = 30.0;
                    resource.Dither = false;
                    resource.AlignWithLayer = true;
                    resource.Reverse = true;
                    resource.HorizontalOffset = 25;
                    resource.VerticalOffset = -15;
                    var newColorPoints = new List<IGradientColorPoint>(resource.ColorPoints);
                    var
                     newTransparencyPoints = new
                    List<IGradientTransparencyPoint>(resource.TransparencyPoints);
                    newColorPoints.Add(new GradientColorPoint()
                    {
                        Color = Color.Violet,
                        Location = 4096,
                        MedianPointLocation = 75
                    });
                    colorPoints[1].Location = 3000;
                    newTransparencyPoints.Add(new GradientTransparencyPoint()
                    {
                        Opacity = 80.0,
                        Location = 4096,
                        MedianPointLocation = 25
                    });
                    transparencyPoints[2].Location = 3000;
                    resource.ColorPoints = newColorPoints.ToArray();
                    resource.TransparencyPoints = newTransparencyPoints.ToArray();
                    im.Save(exportPath);
                }
                break;
            }
            break;
        }
    }
}
```

### Voir également

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* class [FillLayerResource](../filllayerresource)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
