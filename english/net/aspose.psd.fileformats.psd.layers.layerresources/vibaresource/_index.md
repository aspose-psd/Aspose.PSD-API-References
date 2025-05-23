---
title: Class VibAResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VibAResource class. VibA Resource
type: docs
weight: 3670
url: /net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---
{{< psd/tize >}}
## VibAResource class

VibA Resource.

```csharp
public class VibAResource : AdjustmentLayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [VibAResource](vibaresource/)() | Initializes a new instance of the `VibAResource` class. |

## Properties

| Name | Description |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/) { get; } | Gets the layer resource length in bytes. |
| [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| [Saturation](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/) { get; set; } | Gets or sets saturation value |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |
| [Vibrance](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/) { get; set; } | Gets or sets vibrance value |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/) | The type tool info key. |

## Examples

The following code example demonstrates the support of the VibAResource resource.

```csharp
[C#]

// Example of the support of read and write Vibration Resource at runtime.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### See Also

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


