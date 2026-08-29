---
title: "Classe FXidResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FXidResource. La ressource Filter Effects contient des canaux, un masque utilisateur et un masque de feuille pour le filtre intelligent."
type: docs
weight: 2720
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---
{{< psd/tize >}}
## FXidResource class

La ressource d'effets de filtre contient des canaux, un masque utilisateur et un masque de feuille pour le filtre intelligent.

```csharp
public sealed class FXidResource : LayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FXidResource](fxidresource/)(int, int, FilterEffectMaskData[]) | Initialise une nouvelle instance de la classe `FXidResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FilterEffectMasks](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/filtereffectmasks/) { get; } | Obtient les masques d'effet de filtre. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/version/) { get; } | Obtient la version. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [FEidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/feidtypetoolkey/) | La clé d'information de l'outil de type FEid. |
| const [FXidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidtypetoolkey/) | La clé d'information de l'outil de type FXid. |

## Exemples

Cet exemple montre comment obtenir et définir les propriétés de la ressource FXidResource.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
long maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// vérifier après l'enregistrement
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


