---
title: Class LayerMaskDataShort
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort 班级. 定义 LayerMaskDataShort 类其中包含有关 PSD 文件 layer 中的掩码数据的信息当图层仅具有光栅或矢量掩码而不是两者时否则一个LayerMaskDataFull 如果图层只有栅格蒙版ImageData 包含栅格蒙版数据字节 如果图层只有矢量蒙版ImageData 包含矢量蒙版栅格化缓存数据字节 ImageData字节长度应该等于 Width  HeightMaskRectangle属性.
type: docs
weight: 2260
url: /zh/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

定义 LayerMaskDataShort 类，其中包含有关 PSD 文件 layer 中的掩码数据的信息，当图层仅具有光栅或矢量掩码而不是两者时。否则，一个[`LayerMaskDataFull`](../layermaskdatafull/) 如果图层只有栅格蒙版，ImageData 包含栅格蒙版数据字节。 如果图层只有矢量蒙版，ImageData 包含矢量蒙版栅格化（缓存）数据字节。 [`ImageData`](../layermaskdata/imagedata/)字节长度应该等于 Width * Height[`MaskRectangle`](../layermaskdata/maskrectangle/)属性.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | 默认构造函数。 |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | 获取或设置图层蒙版填充。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 获取或设置正确的图层蒙版位置。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 获取或设置顶层遮罩位置。 |

### 也可以看看

* class [LayerMaskData](../layermaskdata/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 部件 [Aspose.PSD](../../)


