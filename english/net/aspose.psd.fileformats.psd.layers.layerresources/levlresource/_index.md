---
title: Class LevlResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource class. Class LevlResource. Resource of Exposure Adjustment Layer
type: docs
weight: 2860
url: /net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

Class LevlResource. Resource of Exposure Adjustment Layer

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Initializes a new instance of the `LevlResource` class. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Initializes a new instance of the `LevlResource` class. Supported in GrayScale, Duotone, RGB, CMYK, Lab color modes 2 bytes - Version (=2) 29 * 10 bytes - Sets of level records with 5 short integers 4 bytes - Lvls header (Starts at 292 index) 2 bytes - Version (=3) 2 bytes - Count of total level record 10 * (Total Count - 29) Zero ending of Lvls resource should be fold for four too |

## Properties

| Name | Description |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Gets the layer resource length in bytes. |
| [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Gets the version. Default is 2 |

## Methods

| Name | Description |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Gets the channel. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | The type tool info key. |

### See Also

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


