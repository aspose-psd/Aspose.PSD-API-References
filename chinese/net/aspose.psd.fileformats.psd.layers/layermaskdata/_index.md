---
title: Class LayerMaskData
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData 班级. 定义基本 LayerMaskData 类其中包含有关 PSD 文件中图层蒙版数据的信息 它可以帮助以编程方式修改 Adobe Photoshop 文件并自动编辑 PSD 格式 如果图层只有光栅蒙版则 ImageData 包含光栅mask data bytes. 如果图层只有矢量蒙版则 ImageData 包含矢量蒙版栅格化缓存数据字节 如果图层同时具有图层和矢量蒙版则 ImageData 包含栅格蒙版和栅格化矢量蒙版组合 这ImageData字节长度应该等于 Width  HeightMaskRectangle properties. 注意仅删除/添加/更新 LayerMaskData 不足以正确保存 因为通道未更新尽管它可能会提供正确的渲染 AddLayerMask方法应该用于那个.
type: docs
weight: 2240
url: /zh/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

定义基本 LayerMaskData 类，其中包含有关 PSD 文件中图层蒙版数据的信息。 它可以帮助以编程方式修改 Adobe® Photoshop® 文件并自动编辑 PSD 格式。 如果图层只有光栅蒙版，则 ImageData 包含光栅mask data bytes. 如果图层只有矢量蒙版，则 ImageData 包含矢量蒙版栅格化（缓存）数据字节。 如果图层同时具有图层和矢量蒙版，则 ImageData 包含栅格蒙版和栅格化矢量蒙版组合。 这[`ImageData`](./imagedata/)字节长度应该等于 Width * Height[`MaskRectangle`](./maskrectangle/) properties. 注意，仅删除/添加/更新 LayerMaskData 不足以正确保存 ，因为通道未更新；尽管它可能会提供正确的渲染。 [`AddLayerMask`](../layer/addlayermask/)方法应该用于那个.

```csharp
public abstract class LayerMaskData
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 获取或设置底层遮罩位置。 |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | 获取layer mask遮罩数据的大小。 |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | 获取或设置默认颜色。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | 获取或设置图层蒙版标志。 |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | 获取或设置 PSD 文件中的图层蒙版数据（或组合/最终蒙版，如果有矢量蒙版）。 |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 获取或设置左侧图层遮罩位置。 |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | 获取或设置掩码[`Rectangle`](../../aspose.psd/rectangle/)PSD 文件中的图层蒙版。 它采用左、右、上和下属性并创建[`Rectangle`](../../aspose.psd/rectangle/) |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 获取或设置正确的图层蒙版位置。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 获取或设置顶层遮罩位置。 |

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 部件 [Aspose.PSD](../../)


