---
title: "Classe FilterEffectMaskData"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FilterEffectMaskData class. La classe de données de masque de filtre"
type: docs
weight: 2740
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData class

La classe de données du masque de filtre.

```csharp
public sealed class FilterEffectMaskData
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FilterEffectMaskData](filtereffectmaskdata/)(string, Rectangle, int, int, ChannelInformation[], ChannelInformation, Rectangle, ChannelInformation) | Initialise une nouvelle instance de la classe `FilterEffectMaskData`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Channels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/channels/) { get; } | Obtient les canaux. |
| [GUID](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/) { get; } | Obtient le GUID. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/length/) { get; } | Obtient la longueur des données du masque de filtre en octets. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maskrectangle/) { get; } | Obtient le rectangle du masque de feuille. |
| [MaxChannels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maxchannels/) { get; } | Obtient le maximum du nombre de canaux. |
| [PixelsDepth](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/pixelsdepth/) { get; } | Obtient la profondeur des pixels. |
| [Rectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/) { get; } | Obtient le rectangle des canaux. |
| [SheetMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/sheetmask/) { get; } | Obtient le masque de feuille. |
| [UserMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/usermask/) { get; } | Obtient le masque utilisateur. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SaveData](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/savedata/)(StreamContainer) | Enregistre la ressource dans le conteneur de flux spécifié. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


