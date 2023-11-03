---
title: Class LayerMaskDataShort
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort class. Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer when the layer has only raster or vector mask but not both. Otherwise a LayerMaskDataFull is used. If the layer has only a raster mask the ImageData contains the raster mask data bytes. If the layer has only a vector mask the ImageData contains the vector mask rasterized cached data bytes. The ImageData bytes length should be equal Width  Height of MaskRectangle properties
type: docs
weight: 2360
url: /net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer when the layer has only raster or vector mask but not both. Otherwise, a [`LayerMaskDataFull`](../layermaskdatafull/) is used. If the layer has only a raster mask the ImageData contains the raster mask data bytes. If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes. The [`ImageData`](../layermaskdata/imagedata/) bytes length should be equal Width * Height of [`MaskRectangle`](../layermaskdata/maskrectangle/) properties.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Constructors

| Name | Description |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | The default constructor. |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Gets or sets the layer mask padding. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Gets or sets the right layer mask position. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Gets or sets the top layer mask position. |

### See Also

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


