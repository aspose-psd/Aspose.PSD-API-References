---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: Aspose.PSD för .NET API-referens
description: FilterEffectMaskData byggare. Initierar en ny instans avFilterEffectMaskData class.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
## FilterEffectMaskData constructor

Initierar en ny instans av[`FilterEffectMaskData`](../) class.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| guid | String | Resursguiden. |
| rectangle | Rectangle | Kanalerna rektangel. |
| pixelsDepth | Int32 | Pixeldjupet. |
| maxChannels | Int32 | Maxvärde för kanaler. |
| channels | ChannelInformation[] | Kanalerna. |
| userMask | ChannelInformation | Användarmasken. |
| maskRectangle | Rectangle | Sheet mask rektangel. |
| sheetMask | ChannelInformation | Sheet masken. |

### Exempel

Det här exemplet visar hur man hämtar och ställer in egenskaper för FXidResource-resursen.

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

// kontrollera efter att du har sparat
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

### Se även

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* hopsättning [Aspose.PSD](../../../)


