---
title: Class BlwhResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BlwhResource classe. La classe BlwhResource est une ressource du calque de réglage noir et blanc.
type: docs
weight: 2320
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---
## BlwhResource class

La classe BlwhResource est une ressource du calque de réglage noir et blanc.

```csharp
public class BlwhResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [BlwhResource](blwhresource/)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BlackAndWhitePresetFileName](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blackandwhitepresetfilename/) { get; set; } | Obtient ou définit le nom du fichier prédéfini noir et blanc. |
| [Blues](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blues/) { get; set; } | Obtient ou définit la valeur de blues. |
| [BwPresetKind](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/bwpresetkind/) { get; set; } | Obtient ou définit la valeur de type prédéfini noir et blanc. |
| [Cyans](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/cyans/) { get; set; } | Obtient ou définit la valeur des cyans. |
| [Greens](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/greens/) { get; set; } | Obtient ou définit la valeur des verts. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/key/) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/length/) { get; } | Obtient la longueur de la ressource de couche en octets. |
| [Magentas](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/magentas/) { get; set; } | Obtient ou définit la valeur magentas. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/psdversion/) { get; } | Obtient la version psd. |
| [Reds](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/reds/) { get; set; } | Obtient ou définit la valeur des rouges. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Obtient la signature. |
| [TintColor](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/tintcolor/) { get; set; } | Obtient ou définit la valeur ARGB de la couleur de teinte. |
| [UseTint](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/usetint/) { get; set; } | Obtient ou définit une valeur indiquant si la [couleur de teinte] est utilisée. |
| [Yellows](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/yellows/) { get; set; } | Obtient ou définit la valeur des jaunes. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/typetoolkey/) | La clé d'informations sur l'outil de type. |

### Exemples

L'exemple suivant montre comment modifier un BlwhResource.

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

const string ActualPropertyValueIsWrongMessage = "Expected property value is not equal to actual value";

string destinationFileName = "Output" + sourceFileName;
bool isRequiredResourceFound = false;
using (PsdImage im = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == tintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == bwPresetKind, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == bwPresetFileName, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue) < 1e-6, ActualPropertyValueIsWrongMessage);

                // Tester l'édition et l'enregistrement
                blwhResource.Reds = reds - 15;
                blwhResource.Yellows = yellows - 15;
                blwhResource.Greens = greens + 15;
                blwhResource.Cyans = cyans + 15;
                blwhResource.Blues = blues - 15;
                blwhResource.Magentas = magentas - 15;
                blwhResource.UseTint = !useTint;
                blwhResource.BwPresetKind = 4;
                blwhResource.BlackAndWhitePresetFileName = "bwPresetFileName";
                blwhLayer.TintColorRed = tintColorRed - 60;
                blwhLayer.TintColorGreen = tintColorGreen - 60;
                blwhLayer.TintColorBlue = tintColorBlue - 60;

                im.Save(destinationFileName);
                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");

isRequiredResourceFound = false;

using (PsdImage im = (PsdImage)Image.Load(destinationFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == !useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == newTintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == 4, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == "bwPresetFileName", ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue + 60) < 1e-6, ActualPropertyValueIsWrongMessage);

                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");
```

### Voir également

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


