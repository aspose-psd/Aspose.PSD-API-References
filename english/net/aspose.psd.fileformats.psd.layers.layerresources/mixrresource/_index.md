---
title: MixrResource
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 2690
url: /net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Class MixrResource. Resource of Channel Mixer Adjustment Layer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [MixrResource](mixrresource)() | Initializes a new instance of the [`MixrResource`](../mixrresource) class. PSD format specification contains following description: 2 Version ( = 1) 2 Monochrome 20 RGB or CMYK color plus constant for the mixer settings. 4 * 2 bytes of color with 2 bytes of constant. |
| [MixrResource](mixrresource)(byte[]) | Initializes a new instance of the [`MixrResource`](../mixrresource) class. PSD format specification contains following description: 2 Version ( = 1) 2 Monochrome 20 RGB or CMYK color plus constant for the mixer settings. 4 * 2 bytes of color with 2 bytes of constant. |

## Properties

| Name | Description |
| --- | --- |
| override [Key](key) { get; } | Gets the layer resource key. |
| override [Length](length) { get; } | Gets the layer resource length in bytes. |
| [Monochrome](monochrome) { get; set; } | Gets or sets a value indicating whether this [`MixrResource`](../mixrresource) is monochrome. |
| override [PsdVersion](psdversion) { get; } | Gets the psd version. |
| [Version](version) { get; set; } | Gets or sets the version. |

## Methods

| Name | Description |
| --- | --- |
| [GetChannelInfo](getchannelinfo)(int) | Gets the channel information raw data |
| [SetChannelInfo](setchannelinfo)(int, byte[]) | Sets the channel information. |

## Other Members

| Name | Description |
| --- | --- |
| const [TypeToolKey](typetoolkey) | The type tool info key. |

### See Also

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* class [AdjustmentLayerResource](../adjustmentlayerresource)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->