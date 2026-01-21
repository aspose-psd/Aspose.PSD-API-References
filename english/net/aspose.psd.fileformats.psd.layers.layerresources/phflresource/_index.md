---
title: Class PhflResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource class. Class PhflResource. Resource of Exposure Adjustment Layer 2 Version   3  or   2  12 4 bytes each for XYZ colorOnly in Version 3 10 2 bytes color space followed by 4  2 bytes color componentOnly in Version 2 4 Density 1 Preserve Luminosity
type: docs
weight: 3210
url: /net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
{{< psd/tize >}}
## PhflResource class

Class PhflResource. Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2) 4 Density 1 Preserve Luminosity

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Properties

| Name | Description |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Gets or sets the density. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Gets the layer resource length in bytes. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Gets or sets a value indicating whether [preserve luminosity]. |
| [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Gets the version. Default is 2 or 3 |

## Methods

| Name | Description |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Gets the color of the RGB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Sets the RGB color. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | The type tool info key. |

### See Also

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


