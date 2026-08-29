---
title: "类 LayerMaskDataFull"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull 类。定义了 LayerMaskDataFull 类，当图层同时拥有图层蒙版和矢量蒙版时，包含 PSD 文件中该图层蒙版数据的信息。否则使用 LayerMaskDataShort。ImageData 包含光栅蒙版和光栅化的矢量蒙版的组合。ImageData 字节长度应等于 MaskRectangle.Width * MaskRectangle.Height 属性。"
type: docs
weight: 2450
url: /zh/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

定义 LayerMaskDataFull 类，当图层同时拥有图层蒙版和矢量蒙版时，包含 PSD 文件中该图层蒙版数据的信息。否则使用 [`LayerMaskDataShort`](../layermaskdatashort/)。ImageData 包含光栅蒙版和光栅化的矢量蒙版的组合。ImageData 字节长度应等于 MaskRectangle.Width * MaskRectangle.Height 属性。

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | 获取或设置背景颜色。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 获取或设置图层蒙版底部位置。 |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | 获取图层蒙版数据的大小。 |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | 获取或设置默认颜色。 |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | 获取或设置 PSD 图像图层中包围的底部光栅蒙版位置。 |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | 获取或设置 PSD 文件图层中包围的左侧光栅蒙版位置。 |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | 获取或设置 PSD 文件图层中包围的右侧光栅蒙版位置。 |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | 获取或设置 PSD 图像图层中光栅蒙版的包围顶部位置。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | 获取或设置图层蒙版标志。 |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | 获取或设置 PSD 文件中图层蒙版数据（如果存在矢量蒙版，则为组合/最终蒙版）。 |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 获取或设置图层蒙版左侧位置。 |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | 获取或设置 PSD 文件中图层蒙版的蒙版 [`Rectangle`](../../aspose.psd/rectangle/)。它接受 left、right、top 和 bottom 属性并创建 [`Rectangle`](../../aspose.psd/rectangle/)。 |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | 获取或设置用于用户/光栅蒙版的图层蒙版标志。对于矢量蒙版，使用 Flags 属性。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 获取或设置图层蒙版右侧位置。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 获取或设置图层蒙版顶部位置。 |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | 获取或设置 PSD 文件中图层的用户（光栅）蒙版数据。（MaskData 属性中有光栅化的矢量蒙版）。 |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | 获取或设置 PSD 图像图层中的用户蒙版（包围）矩形。 |

### 另请参阅

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


