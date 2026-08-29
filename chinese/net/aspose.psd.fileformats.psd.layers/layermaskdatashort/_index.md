---
title: "类 LayerMaskDataShort"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort 类。定义了 LayerMaskDataShort 类，当图层仅拥有光栅蒙版或矢量蒙版但不同时拥有两者时，包含 PSD 文件中该图层蒙版数据的信息。否则使用 LayerMaskDataFull。如果图层只有光栅蒙版，ImageData 包含光栅蒙版数据字节。如果图层只有矢量蒙版，ImageData 包含矢量蒙版光栅化的缓存数据字节。ImageData 字节长度应等于 MaskRectangle 属性的 Width * Height。"
type: docs
weight: 2460
url: /zh/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

定义 LayerMaskDataShort 类，当图层仅拥有光栅蒙版或矢量蒙版但不同时拥有两者时，包含 PSD 文件中该图层蒙版数据的信息。否则使用 [`LayerMaskDataFull`](../layermaskdatafull/)。如果图层只有光栅蒙版，ImageData 包含光栅蒙版数据字节。如果图层只有矢量蒙版，ImageData 包含矢量蒙版光栅化（缓存）的数据字节。[`ImageData`](../layermaskdata/imagedata/) 字节长度应等于 [`MaskRectangle`](../layermaskdata/maskrectangle/) 属性的 Width * Height。

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | 初始化 `LayerMaskDataShort` 类的新实例。 |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | 获取或设置图层遮罩填充。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 获取或设置图层蒙版右侧位置。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 获取或设置图层蒙版顶部位置。 |

### 另请参阅

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


