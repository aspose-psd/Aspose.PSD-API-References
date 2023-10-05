---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD for .NET API Reference
description: The namespace contains PSD file format layers
type: docs
weight: 230
url: /net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
The namespace contains PSD file format layers.

## Classes

| Class | Description |
| --- | --- |
| [BlendRange](./blendrange/) | The blend range. |
| [ChannelInformation](./channelinformation/) | The channel information. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | The global layer mask section. |
| [Layer](./layer/) | The psd layer. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | The layer blending ranges data. |
| [LayerGroup](./layergroup/) | Group layer class |
| [LayerHashCalculator](./layerhashcalculator/) | Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files |
| [LayerMaskData](./layermaskdata/) | Defines base LayerMaskData class which contains information about the layer mask data in the PSD file. It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing. If the layer has only a raster mask the ImageData contains the raster mask data bytes. If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes. If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined. The [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) bytes length should be equal Width * Height of [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving because channels are not updated; though it may provide correct rendering. The [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) method should be used for that. |
| [LayerMaskDataFull](./layermaskdatafull/) | Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer when the layer has both layer and vector masks. Otherwise, a [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used. The ImageData contains the raster mask and the rasterized vector mask combined. The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties. |
| [LayerMaskDataShort](./layermaskdatashort/) | Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer when the layer has only raster or vector mask but not both. Otherwise, a [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used. If the layer has only a raster mask the ImageData contains the raster mask data bytes. If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes. The [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) bytes length should be equal Width * Height of [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. |
| [LayerResource](./layerresource/) | Represents layer info. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Define the the layer resources registry for PSD files loading. |
| [LinkedLayersManager](./linkedlayersmanager/) | Linked layers manager class. |
| [SectionDividerLayer](./sectiondividerlayer/) | The section divider layer to mark the bounds of the folder (layer group). |
| [ShapeLayer](./shapelayer/) | Shape layer. Encapsulates the logic of work with Shape layer and related resources. |
| [TextLayer](./textlayer/) | The text layer class |
## Interfaces

| Interface | Description |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Base interface for fill settings |
| [ILayerResourceLoader](./ilayerresourceloader/) | The layer resource loader. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [LayerFlags](./layerflags/) | The layer flags |
| [LayerMaskFlags](./layermaskflags/) | The layer mask flags |


