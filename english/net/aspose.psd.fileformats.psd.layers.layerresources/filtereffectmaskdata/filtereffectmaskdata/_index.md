---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: Aspose.PSD for .NET API Reference
description: FilterEffectMaskData constructor. Initializes a new instance of the FilterEffectMaskData class
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

Initializes a new instance of the [`FilterEffectMaskData`](../) class.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Parameter | Type | Description |
| --- | --- | --- |
| guid | String | The resource guid. |
| rectangle | Rectangle | The channels rectangle. |
| pixelsDepth | Int32 | The pixels depth. |
| maxChannels | Int32 | The max channels value. |
| channels | ChannelInformation[] | The channels. |
| userMask | ChannelInformation | The user mask. |
| maskRectangle | Rectangle | The sheet mask rectangle. |
| sheetMask | ChannelInformation | The sheet mask. |

## Examples

This example demonstrates how to get and set properties of the FXidResource resource.

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

// check after saving
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

### See Also

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


