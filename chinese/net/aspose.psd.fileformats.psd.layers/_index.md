---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD for .NET API 参考"
description: "该命名空间包含 PSD 文件格式层"
type: docs
weight: 230
url: /zh/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
该命名空间包含 PSD 文件格式的图层。

## 类

| 类 | 描述 |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | 画板图层类。 |
| [BlendRange](./blendrange/) | 混合范围。 |
| [ChannelInformation](./channelinformation/) | 通道信息。 |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | 全局图层蒙版部分。 |
| [Layer](./layer/) | PSD 图层。 |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | 图层混合范围数据。 |
| [LayerGroup](./layergroup/) | 组图层类 |
| [LayerHashCalculator](./layerhashcalculator/) | PSD 图层的哈希计算器。它可用于在不同的 PSD 文件中查找相同或不同的图层。 |
| [LayerMaskData](./layermaskdata/) | 定义基础 LayerMaskData 类，包含 PSD 文件中图层蒙版数据的信息。它可以帮助以编程方式修改 Adobe® Photoshop® 文件并自动化 PSD 格式编辑。如果图层仅有光栅蒙版，`ImageData` 包含光栅蒙版数据字节。如果图层仅有矢量蒙版，`ImageData` 包含矢量蒙版的光栅化（缓存）数据字节。如果图层同时拥有图层蒙版和矢量蒙版，`ImageData` 包含光栅蒙版和光栅化矢量蒙版的组合。[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) 的字节长度应等于 [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) 属性的 Width * Height。请注意，仅删除/添加/更新 LayerMaskData 并不足以正确保存，因为通道未更新；尽管它可能提供正确的渲染。应使用 [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) 方法。 |
| [LayerMaskDataFull](./layermaskdatafull/) | 定义 LayerMaskDataFull 类，当图层同时拥有图层蒙版和矢量蒙版时，包含 PSD 文件中该图层的蒙版数据信息。否则，使用 [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/)。`ImageData` 包含光栅蒙版和光栅化矢量蒙版的组合。`ImageData` 的字节长度应等于 MaskRectangle.Width * MaskRectangle.Height 属性。 |
| [LayerMaskDataShort](./layermaskdatashort/) | 定义 LayerMaskDataShort 类，当图层仅拥有光栅蒙版或矢量蒙版但不同时拥有两者时，包含 PSD 文件中该图层的蒙版数据信息。否则，使用 [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/)。如果图层仅有光栅蒙版，`ImageData` 包含光栅蒙版数据字节。如果图层仅有矢量蒙版，`ImageData` 包含矢量蒙版的光栅化（缓存）数据字节。[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) 的字节长度应等于 [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) 的 Width * Height 属性。 |
| [LayerResource](./layerresource/) | 表示图层信息。 |
| [LayerResourcesRegistry](./layerresourcesregistry/) | 定义 PSD 文件加载的图层资源注册表。 |
| [LinkedLayersManager](./linkedlayersmanager/) | 链接图层管理器类。 |
| [SectionDividerLayer](./sectiondividerlayer/) | 用于标记文件夹（图层组）边界的分段层。 |
| [ShapeLayer](./shapelayer/) | 形状图层。封装了对形状图层及相关资源的操作逻辑。 |
| [TextLayer](./textlayer/) | 文本图层类 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | 基础填充设置接口 |
| [ILayerResourceLoader](./ilayerresourceloader/) | 图层资源加载器。 |
| [IShapeLayer](./ishapelayer/) | 描述形状图层的属性。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [LayerFlags](./layerflags/) | 图层标志 |
| [LayerMaskFlags](./layermaskflags/) | 图层蒙版标志 |


