---
title: "FilterEffectMaskData.FilterEffectMaskData"
second_title: "Aspose.PSD för .NET API‑referens"
description: "FilterEffectMaskData konstruktör. Initierar en ny instans av FilterEffectMaskData-klassen"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

Initierar en ny instans av klassen [`FilterEffectMaskData`](../).

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| guid | String | Resursens guid. |
| rektangel | Rectangle | Rektangeln för kanalerna. |
| pixelsDepth | Int32 | Pixelns djup. |
| maxChannels | Int32 | Det maximala kanalvärdet. |
| kanaler | ChannelInformation[] | Kanalerna. |
| userMask | ChannelInformation | Användarmasken. |
| maskRectangle | Rectangle | Maskrektangel för bladet. |
| sheetMask | ChannelInformation | Arkmasken. |

## Exempel

Detta exempel visar hur man hämtar och anger egenskaper för FXidResource-resursen.

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

// kontrollera efter sparning
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


