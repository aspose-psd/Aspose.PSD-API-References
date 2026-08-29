---
title: "类 LayerMaskData"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData 类。定义了基类 LayerMaskData，包含 PSD 文件中图层蒙版数据的信息。它可以帮助以编程方式修改 Adobe Photoshop 文件并自动化 PSD 格式编辑。如果图层只有光栅蒙版，ImageData 包含光栅蒙版数据字节。如果图层只有矢量蒙版，ImageData 包含矢量蒙版光栅化的缓存数据字节。如果图层同时拥有图层蒙版和矢量蒙版，ImageData 包含光栅蒙版和光栅化的矢量蒙版的组合。ImageData 字节长度应等于 MaskRectangle 属性的 Width * Height。请注意，仅删除/添加/更新 LayerMaskData 并不足以正确保存，因为通道未更新，尽管可能提供正确的渲染。应使用 AddLayerMask 方法来完成此操作。"
type: docs
weight: 2440
url: /zh/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

定义基类 LayerMaskData，包含 PSD 文件中图层蒙版数据的信息。它可以帮助以编程方式修改 Adobe® Photoshop® 文件并自动化 PSD 格式编辑。如果图层只有光栅蒙版，ImageData 包含光栅蒙版数据字节。如果图层只有矢量蒙版，ImageData 包含矢量蒙版光栅化（缓存）的数据字节。如果图层同时拥有图层蒙版和矢量蒙版，ImageData 包含光栅蒙版和光栅化的矢量蒙版的组合。[`ImageData`](./imagedata/) 字节长度应等于 [`MaskRectangle`](./maskrectangle/) 属性的 Width * Height。请注意，仅删除/添加/更新 LayerMaskData 并不足以正确保存，因为通道未更新；尽管可能提供正确的渲染。应使用 [`AddLayerMask`](../layer/addlayermask/) 方法来完成此操作。

```csharp
public abstract class LayerMaskData
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 获取或设置图层蒙版底部位置。 |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | 获取图层蒙版数据的大小。 |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | 获取或设置默认颜色。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | 获取或设置图层蒙版标志。 |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | 获取或设置 PSD 文件中图层蒙版数据（如果存在矢量蒙版，则为组合/最终蒙版）。 |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 获取或设置图层蒙版左侧位置。 |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | 获取或设置 PSD 文件中图层蒙版的蒙版 [`Rectangle`](../../aspose.psd/rectangle/)。它接受 left、right、top 和 bottom 属性并创建 [`Rectangle`](../../aspose.psd/rectangle/)。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 获取或设置图层蒙版右侧位置。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 获取或设置图层蒙版顶部位置。 |

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


