---
title: Class SoCoResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource class. Class SoCoResource. This resource contains information about Color Fill Layers
type: docs
weight: 3320
url: /net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
{{< psd/tize >}}
## SoCoResource class

Class SoCoResource. This resource contains information about Color Fill Layers

```csharp
public class SoCoResource : FillLayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [SoCoResource](socoresource/)() | Initializes a new instance of the `SoCoResource` class. |

## Properties

| Name | Description |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | Gets the RGB color . |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | Gets the layer resource length in bytes. |
| [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | The type tool info key. |

## Examples

The following example demonstrates how you edit SoCoResource (Layer Resource for Color Fill Layer)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Load an existing image into an instance of PsdImage class
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Finding of FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Finding of SoCoResource in Layer Resource List
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // Setting the SoCoResource Color property
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### See Also

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


