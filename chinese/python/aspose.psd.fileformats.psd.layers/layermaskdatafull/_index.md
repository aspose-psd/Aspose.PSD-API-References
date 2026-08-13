---
title: "LayerMaskDataFull 类"
type: docs
weight: 980
url: /zh/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | 初始化 LayerMaskDataFull 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | byte | 读/写 | 获取或设置背景颜色。 |
| 底部 | int | 读/写 | 获取或设置底部图层蒙版位置。 |
| data_size | int | r | 获取图层蒙版数据的大小。 |
| default_color | byte | 读/写 | 获取或设置默认颜色。 |
| enclosing_bottom | int | 读/写 | 获取或设置 PSD 图像图层中封闭底部光栅蒙版位置。 |
| enclosing_left | int | 读/写 | 获取或设置 PSD 文件图层中封闭左侧光栅蒙版位置。 |
| enclosing_right | int | 读/写 | 获取或设置 PSD 文件图层中封闭右侧光栅蒙版位置。 |
| enclosing_top | int | 读/写 | 获取或设置 PSD 图像图层中光栅蒙版的封闭顶部位置。 |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | 获取或设置图层蒙版标志。 |
| image_data | byte | 读/写 | 获取或设置 PSD 文件中图层蒙版数据（如果存在矢量蒙版，则为合并/最终蒙版）。 |
| left | int | 读/写 | 获取或设置左侧图层蒙版位置。 |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | 获取或设置 PSD 文件中图层蒙版的掩码 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。<br/>            它接受 left、right、top 和 bottom 属性并创建 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | 获取或设置用于用户/光栅掩码的图层掩码标志。对于矢量掩码，使用 Flags 属性。 |
| right | int | 读/写 | 获取或设置右侧图层蒙版位置。 |
| top | int | 读/写 | 获取或设置顶部图层蒙版位置。 |
| user_mask_data | byte | 读/写 | 获取或设置 PSD 文件中图层的用户（光栅）掩码数据。（在 MaskData 属性中有一个光栅化的矢量掩码）。 |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | 获取或设置 PSD 图像图层中的用户掩码（包围）矩形。 |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

初始化 LayerMaskDataFull 类的新实例

