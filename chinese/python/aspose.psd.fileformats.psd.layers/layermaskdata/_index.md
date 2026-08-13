---
title: "LayerMaskData 类"
type: docs
weight: 970
url: /zh/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 底部 | int | 读/写 | 获取或设置底部图层蒙版位置。 |
| data_size | int | r | 获取图层蒙版数据的大小。 |
| default_color | byte | 读/写 | 获取或设置默认颜色。 |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | 获取或设置图层蒙版标志。 |
| image_data | byte | 读/写 | 获取或设置 PSD 文件中图层蒙版数据（如果存在矢量蒙版，则为合并/最终蒙版）。 |
| left | int | 读/写 | 获取或设置左侧图层蒙版位置。 |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | 获取或设置 PSD 文件中图层蒙版的掩码 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。<br/>            它接受 left、right、top 和 bottom 属性并创建 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |
| right | int | 读/写 | 获取或设置右侧图层蒙版位置。 |
| top | int | 读/写 | 获取或设置顶部图层蒙版位置。 |


