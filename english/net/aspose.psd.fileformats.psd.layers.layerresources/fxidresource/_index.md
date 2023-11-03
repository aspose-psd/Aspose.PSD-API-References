---
title: Class FXidResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FXidResource class. The Filter Effects resource contains channels a user mask and a sheet mask for the smart filter
type: docs
weight: 2560
url: /net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---
{{< psd/tize >}}
## FXidResource class

The Filter Effects resource contains channels, a user mask, and a sheet mask for the smart filter.

```csharp
public sealed class FXidResource : LayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [FXidResource](fxidresource/)(int, int, FilterEffectMaskData[]) | Initializes a new instance of the `FXidResource` class. |

## Properties

| Name | Description |
| --- | --- |
| [FilterEffectMasks](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/filtereffectmasks/) { get; } | Gets the filter effect masks. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/length/) { get; } | Gets the layer resource length in bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/signature/) { get; } | Gets the layer resource signature. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/version/) { get; } | Gets the version. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [FEidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/feidtypetoolkey/) | The type tool info key FEid. |
| const [FXidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidtypetoolkey/) | The type tool info key FXid. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


