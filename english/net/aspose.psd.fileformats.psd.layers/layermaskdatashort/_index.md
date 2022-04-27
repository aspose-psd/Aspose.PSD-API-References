---
title: LayerMaskDataShort
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 2150
url: /net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer when the layer has only raster or vector mask but not both. Otherwise, a [`LayerMaskDataFull`](../layermaskdatafull) is used. If the layer has only a raster mask the ImageData contains the raster mask data bytes. If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes. The [`ImageData`](../layermaskdata/imagedata) bytes length should be equal Width * Height of [`MaskRectangle`](../layermaskdata/maskrectangle) properties.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Constructors

| Name | Description |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Padding](padding) { get; set; } | Gets or sets the layer mask padding. |

### See Also

* class [LayerMaskData](../layermaskdata)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->