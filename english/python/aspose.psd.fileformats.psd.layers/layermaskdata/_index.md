---
title: LayerMaskData Class
type: docs
weight: 910
url: /python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.1.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | Gets or sets the bottom layer mask position. |
| data_size | int | r | Gets the size of the layer mask mask data. |
| default_color | byte | r/w | Gets or sets the default color. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Gets or sets the layer mask flags. |
| image_data | byte | r/w | Gets or sets the layer mask data (or combined / final mask if there is a vector mask) in the PSD file. |
| left | int | r/w | Gets or sets the left layer mask position. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Gets or sets the mask [Rectangle](/psd/python-net/aspose.psd/rectangle/) of the layer mask in the PSD file.<br/>            It takes left, right, top and bottom properties and creates [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| right | int | r/w | Gets or sets the right layer mask position. |
| top | int | r/w | Gets or sets the top layer mask position. |


