---
title: Class LayerMaskDataFull
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull class. Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer when the layer has both layer and vector masks. Otherwise a LayerMaskDataShort is used. The ImageData contains the raster mask and the rasterized vector mask combined. The ImageData bytes length should be equal MaskRectangle.Width  MaskRectangle.Height properties
type: docs
weight: 2430
url: /net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer when the layer has both layer and vector masks. Otherwise, a [`LayerMaskDataShort`](../layermaskdatashort/) is used. The ImageData contains the raster mask and the rasterized vector mask combined. The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Constructors

| Name | Description |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Gets or sets the background color. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Gets or sets the bottom layer mask position. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Gets the size of the layer mask mask data. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Gets or sets the default color. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Gets or sets the enclosing bottom raster mask position in the PSD image layer. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Gets or sets the enclosing left raster mask position in the PSD file layer. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Gets or sets the enclosing right raster mask position in the PSD file layer. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Gets or sets the enclosing top position of the raster mask in the PSD image layer. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Gets or sets the layer mask flags. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Gets or sets the layer mask data (or combined / final mask if there is a vector mask) in the PSD file. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Gets or sets the left layer mask position. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Gets or sets the mask [`Rectangle`](../../aspose.psd/rectangle/) of the layer mask in the PSD file. It takes left, right, top and bottom properties and creates [`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Gets or sets the layer mask flags that is used for user / raster mask. For vector mask the Flags property is used. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Gets or sets the right layer mask position. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Gets or sets the top layer mask position. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Gets or sets the user (raster) mask data of a layer in the PSD file. (There is a rasterized vector mask in the MaskData property). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Gets or sets the user mask (enclosing) rectangle in the PSD image layer.. |

### See Also

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


