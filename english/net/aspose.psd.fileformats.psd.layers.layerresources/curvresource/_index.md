---
title: Class CurvResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource class. Class CurvResource. Resource of Curves Adjustment Layer 1 byte  0 if use curves 1 if used pixels on map if 0 then 2 bytes  short. Default is 1 4 bytes  int. Used only last byte by bit. First bit is for 1 channel the Fourth bit for 4 channel for example 2 bytes  short points count 4 bytes  count of point  points of curve 2 short first position second height 4 bytes  word Crv  2 bytes  short default is 4 for Curves 4 bytes  int. Default is 1 4 bytes  point count 4 bytes  point count  points of curve 2 short first position second height 04 bytes  Leading to be fold for four if 1 then 2 bytes  short. Default is 1 4 bytes  int. Used only last byte. One channel is in one bit. First bit is for 1 channel the Fourth bit for 4 channel for example 256  count of changed channels  ordered values of channel in range 0  255 4 bytes  word Crv  2 bytes  short. Default is 3 for pixels on map 4 bytes  int Channel count 2  256 bytes  short 2 for channel index 256 is ordered values of channel in range 0  255
type: docs
weight: 2430
url: /net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

Class CurvResource. Resource of Curves Adjustment Layer 1 byte - 0 if use curves, 1 if used pixels on map if 0 then: 2 bytes - short. Default is 1 4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example 2 bytes - short points count 4 bytes * count of point - points of curve 2 short: first position, second height 4 bytes - word "Crv " 2 bytes - short default is 4 for Curves 4 bytes - int. Default is 1 4 bytes - point count 4 bytes * point count - points of curve 2 short: first position, second height 0-4 bytes - Leading to be fold for four if 1 then: 2 bytes - short. Default is 1 4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example 256 * count of changed channels - ordered values of channel in range 0 - 255 4 bytes - word "Crv " 2 bytes - short. Default is 3 for pixels on map 4 bytes - int Channel count (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Initializes a new instance of the `CurvResource` class. |
| [CurvResource](curvresource/#constructor_1)(int) | Initializes a new instance of the `CurvResource` class. |

## Properties

| Name | Description |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Gets or sets a value indicating whether this instance is data stored discrete. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Gets the layer resource length in bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion/) { get; } | Gets the psd version. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Gets the signature. |

## Methods

| Name | Description |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Gets the active manager. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Gets the channel data. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Gets the curve manager. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
<<<<<<< HEAD
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | The type tool info key. |
=======
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey) | The type tool info key. |
>>>>>>> production

### See Also

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


