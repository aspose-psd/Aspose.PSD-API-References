---
title: Class NvrtResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource class. Class NvrtResource. Resource of Invert Adjustment Layer
type: docs
weight: 2970
url: /net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
{{< psd/tize >}}
## NvrtResource class

Class NvrtResource. Resource of Invert Adjustment Layer.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | Initializes a new instance of the `NvrtResource` class. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | Initializes a new instance of the `NvrtResource` class. |

## Properties

| Name | Description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | Gets the layer resource length in bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/psdversion/) { get; } | Gets the PSD version. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Gets the signature. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | The type tool info key. |

## Examples

The following example demonstrates how to get NvrtResource.

```csharp
[C#]

string sourceFilePath = "InvertAdjustmentLayer.psd";
NvrtResource resource = null;
using (PsdImage psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    foreach (Aspose.PSD.FileFormats.Psd.Layers.Layer layer in psdImage.Layers)
    {
        if (layer is InvertAdjustmentLayer)
        {
            foreach (Aspose.PSD.FileFormats.Psd.Layers.LayerResource layerResource in layer.Resources)
            {
                if (layerResource is NvrtResource)
                {
                    // The NvrtResource is supported.
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### See Also

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


