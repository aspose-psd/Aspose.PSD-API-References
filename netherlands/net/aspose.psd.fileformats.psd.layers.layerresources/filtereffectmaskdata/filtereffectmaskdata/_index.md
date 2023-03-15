---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: Aspose.PSD voor .NET API-referentie
description: FilterEffectMaskData constructeur. Initialiseert een nieuw exemplaar van hetFilterEffectMaskData klasse.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
## FilterEffectMaskData constructor

Initialiseert een nieuw exemplaar van het[`FilterEffectMaskData`](../) klasse.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| guid | String | De bronnengids. |
| rectangle | Rectangle | De kanalen rechthoek. |
| pixelsDepth | Int32 | De pixeldiepte. |
| maxChannels | Int32 | De maximale kanalenwaarde. |
| channels | ChannelInformation[] | De kanalen. |
| userMask | ChannelInformation | Het gebruikersmasker. |
| maskRectangle | Rectangle | De rechthoek van het bladmasker. |
| sheetMask | ChannelInformation | Het sheetmasker. |

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* montage [Aspose.PSD](../../../)


