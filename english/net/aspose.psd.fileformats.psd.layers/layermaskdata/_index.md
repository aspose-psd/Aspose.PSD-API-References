---
title: Class LayerMaskData
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData class. Defines base LayerMaskData class which contains information about the layer mask data in the PSD file. It can help to modify Adobe Photoshop files programmatically and automate PSD format editing. If the layer has only a raster mask the ImageData contains the raster mask data bytes. If the layer has only a vector mask the ImageData contains the vector mask rasterized cached data bytes. If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined. The ImageData bytes length should be equal Width  Height of MaskRectangle properties. Notice that just removing / adding / updating the LayerMaskData is not enough for correct saving because channels are not updated though it may provide correct rendering. The AddLayerMask method should be used for that
type: docs
weight: 2420
url: /net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

Defines base LayerMaskData class which contains information about the layer mask data in the PSD file. It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing. If the layer has only a raster mask the ImageData contains the raster mask data bytes. If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes. If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined. The [`ImageData`](./imagedata/) bytes length should be equal Width * Height of [`MaskRectangle`](./maskrectangle/) properties. Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving because channels are not updated; though it may provide correct rendering. The [`AddLayerMask`](../layer/addlayermask/) method should be used for that.

```csharp
public abstract class LayerMaskData
```

## Properties

| Name | Description |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Gets or sets the bottom layer mask position. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Gets the size of the layer mask mask data. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Gets or sets the default color. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Gets or sets the layer mask flags. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Gets or sets the layer mask data (or combined / final mask if there is a vector mask) in the PSD file. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Gets or sets the left layer mask position. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Gets or sets the mask [`Rectangle`](../../aspose.psd/rectangle/) of the layer mask in the PSD file. It takes left, right, top and bottom properties and creates [`Rectangle`](../../aspose.psd/rectangle/) |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Gets or sets the right layer mask position. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Gets or sets the top layer mask position. |

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


