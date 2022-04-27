---
title: SmartObjectResource
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 2840
url: /net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---
## SmartObjectResource class

Defines the SmartObjectResource class that contains information about a smart object layer in a PSD file. Is is the base class for Sold and Sole resources that is used to support smart object layers in the Adobe® Photoshop® images.

```csharp
public abstract class SmartObjectResource : PlacedResource, ISmartObjectLayerResource
```

## Properties

| Name | Description |
| --- | --- |
| override [AntiAliasPolicy](antialiaspolicy) { get; set; } | Gets or sets the anti alias policy of the smart object layer data in the PSD image. |
| [Comp](comp) { get; set; } | Gets or sets the comp value of the smart object layer data in the PSD file. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](compid) { get; set; } | Gets or sets the ID of the currently selected comp for the child document, which will be -1 if none are selected. Comps are compositions of a page layout which designers can create. Using layer comps, you can create, manage, and view multiple versions of a layout in a single Adobe® Photoshop® file. A layer comp is a snapshot of a state of the Layers panel. Layer comps save three types of layer options but this property gets the Layer Comp selection identifier for he smart object layer in the PSD file. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](crop) { get; set; } | Gets or sets the crop of the smart object layer data in the PSD image. |
| [DurationDenominator](durationdenominator) { get; set; } | Gets or sets the duration denominator. |
| [DurationNumerator](durationnumerator) { get; set; } | Gets or sets the duration numerator. |
| [FrameCount](framecount) { get; set; } | Gets or sets the frame count of the smart object layer data in the PSD file. |
| [FrameStepDenominator](framestepdenominator) { get; set; } | Gets or sets the frame step denominator. |
| [FrameStepNumerator](framestepnumerator) { get; set; } | Gets or sets the frame step numerator. |
| [Height](height) { get; set; } | Gets or sets the height. |
| override [Items](items) { get; set; } | Gets or sets the descriptor items of the smart object layer data in the PSD file. |
| override [Length](length) { get; } | Gets the smart object resource length in bytes. |
| [NonAffineTransformMatrix](nonaffinetransformmatrix) { get; set; } | Gets or sets the non affine transform matrix of the smart object layer data in the PSD file. |
| [OriginalCompId](originalcompid) { get; } | Gets the original ID of the currently selected Comp for the child document, which will be -1 if none are selected. This property gets the original layer Comp selection identifier for he smart object layer in the PSD file. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](pagenumber) { get; set; } | Gets or sets the page number of the smart object layer data in the PSD file. |
| [PlacedId](placedid) { get; set; } | Gets or sets the unique identifier of this smart object layer data in the PSD image. |
| override [PlacedLayerType](placedlayertype) { get; set; } | Gets or sets the type of the smart object layer data in the PSD file. |
| override [PsdVersion](psdversion) { get; } | Gets the minimal psd version required for the smart object resource. 0 indicates no restrictions. |
| [Resolution](resolution) { get; set; } | Gets or sets the resolution of the smart object layer data in the PSD file. |
| [ResolutionUnit](resolutionunit) { get; set; } | Gets or sets the resolution measure unit of the smart object layer data in the PSD file. |
| override [Signature](signature) { get; } | Gets the smart object resource signature. |
| override [TotalPages](totalpages) { get; set; } | Gets or sets the total pages number of the smart object layer data in the PSD file. |
| override [TransformMatrix](transformmatrix) { get; set; } | Gets or sets the transform matrix of the smart object layer data in the PSD file. |
| override [UniqueId](uniqueid) { get; set; } | Gets or sets the global unique identifier of the smart object layer data [`SmartObjectResource`](../smartobjectresource) in the PSD image. |
| [Width](width) { get; set; } | Gets or sets the width. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](save)(StreamContainer, int) | Saves the smart object resource to the specified stream container. |

### See Also

* class [SoLdResource](../soldresource)
* class [SoLeResource](../soleresource)
* class [PlacedResource](../placedresource)
* interface [ISmartObjectLayerResource](../ismartobjectlayerresource)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
