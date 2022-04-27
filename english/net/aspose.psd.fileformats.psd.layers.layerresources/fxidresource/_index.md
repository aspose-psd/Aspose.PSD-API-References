---
title: FXidResource
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 2340
url: /net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---
## FXidResource class

The Filter Effects resource contains channels, a user mask, and a sheet mask for the smart filter.

```csharp
public sealed class FXidResource : LayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [FXidResource](fxidresource)(int, int, FilterEffectMaskData[]) | Initializes a new instance of the [`FXidResource`](../fxidresource) class. |

## Properties

| Name | Description |
| --- | --- |
| [FilterEffectMasks](filtereffectmasks) { get; } | Gets the filter effect masks. |
| override [Key](key) { get; } | Gets the layer resource key. |
| override [Length](length) { get; } | Gets the layer resource length in bytes. |
| override [PsdVersion](psdversion) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| override [Signature](signature) { get; } | Gets the layer resource signature. |
| [Version](version) { get; } | Gets the version. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](save)(StreamContainer, int) | Saves the resource to the specified stream container. |

## Other Members

| Name | Description |
| --- | --- |
| const [FEidTypeToolKey](feidtypetoolkey) | The type tool info key FEid. |
| const [FXidTypeToolKey](fxidtypetoolkey) | The type tool info key FXid. |

### See Also

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->