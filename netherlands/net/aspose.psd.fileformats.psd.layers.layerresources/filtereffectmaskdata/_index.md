---
title: Class FilterEffectMaskData
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FilterEffectMaskData klas. De gegevensklasse van het filtermasker.
type: docs
weight: 2480
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---
## FilterEffectMaskData class

De gegevensklasse van het filtermasker.

```csharp
public sealed class FilterEffectMaskData
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [FilterEffectMaskData](filtereffectmaskdata/)(string, Rectangle, int, int, ChannelInformation[], ChannelInformation, Rectangle, ChannelInformation) | Initialiseert een nieuw exemplaar van het`FilterEffectMaskData` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Channels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/channels/) { get; } | Haalt de kanalen op. |
| [GUID](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/) { get; } | Haalt de GUID op. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/length/) { get; } | Haalt de gegevenslengte van het filtermasker op in bytes. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maskrectangle/) { get; } | Hiermee krijgt u de rechthoek van het bladmasker. |
| [MaxChannels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maxchannels/) { get; } | Haalt het maximale aantal kanalen op. |
| [PixelsDepth](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/pixelsdepth/) { get; } | Haalt de pixeldiepte op. |
| [Rectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/) { get; } | Krijgt de kanalen rechthoek. |
| [SheetMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/sheetmask/) { get; } | Haalt het bladmasker op. |
| [UserMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/usermask/) { get; } | Haalt het gebruikersmasker op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [SaveData](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/savedata/)(StreamContainer) | Slaat de bron op in de opgegeven streamcontainer. |

### Voorbeelden

Dit voorbeeld laat zien hoe u eigenschappen van de FXidResource-resource kunt ophalen en instellen.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
int maskLength = 369;

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

// controleren na opslaan
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

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


