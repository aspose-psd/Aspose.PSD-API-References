---
title: FilterEffectMaskData.Rectangle
second_title: Aspose.PSD for .NET API Reference
description: FilterEffectMaskData property. Gets the channels rectangle
type: docs
weight: 80
url: /net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/
---
{{< psd/tize >}}
## FilterEffectMaskData.Rectangle property

Gets the channels rectangle.

```csharp
public Rectangle Rectangle { get; }
```

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
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* assembly [Aspose.PSD](../../../)


