---
title: Class LayerMaskDataFull
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull 班级. 定义 LayerMaskDataFull 类其中包含有关 PSD 文件 layer 中的蒙版数据的信息当图层同时具有图层和矢量蒙版时否则一个LayerMaskDataShort ImageData 包含光栅蒙版和光栅化矢量蒙版的组合 ImageData 字节长度应等于 MaskRectangle.Width  MaskRectangle.Height 属性
type: docs
weight: 2250
url: /zh/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

定义 LayerMaskDataFull 类，其中包含有关 PSD 文件 layer 中的蒙版数据的信息，当图层同时具有图层和矢量蒙版时。否则，一个[`LayerMaskDataShort`](../layermaskdatashort/) ImageData 包含光栅蒙版和光栅化矢量蒙版的组合。 ImageData 字节长度应等于 MaskRectangle.Width * MaskRectangle.Height 属性。

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | 获取或设置背景颜色。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 获取或设置底层遮罩位置。 |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | 获取layer mask遮罩数据的大小。 |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | 获取或设置默认颜色。 |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | 获取或设置 PSD 图像层中封闭的底部光栅蒙版位置。 |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | 获取或设置 PSD 文件图层中封闭的左栅格蒙版位置。 |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | 获取或设置 PSD 文件图层中封闭的右侧光栅掩模位置。 |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | 获取或设置光栅蒙版在PSD图层中的封闭顶部位置。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | 获取或设置图层蒙版标志。 |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | 获取或设置 PSD 文件中的图层蒙版数据（或组合/最终蒙版，如果有矢量蒙版）。 |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 获取或设置左侧图层遮罩位置。 |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | 获取或设置掩码[`Rectangle`](../../aspose.psd/rectangle/)PSD 文件中的图层蒙版。 它采用左、右、上和下属性并创建[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | 获取或设置用于用户/光栅掩码的层掩码标志。对于矢量蒙版，使用 Flags 属性。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 获取或设置正确的图层蒙版位置。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 获取或设置顶层遮罩位置。 |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | 获取或设置PSD文件中图层的用户（光栅）掩码数据。 （在 MaskData 属性中有一个评级矢量掩码）。 |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | 获取或设置 PSD 图像层中的用户遮罩（封闭）矩形.. |

### 也可以看看

* class [LayerMaskData](../layermaskdata/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 部件 [Aspose.PSD](../../)


