---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD for .NET API 参考
description: 命名空间包含 PSD 文件格式图层
type: docs
weight: 210
url: /zh/net/aspose.psd.fileformats.psd.layers/
---
命名空间包含 PSD 文件格式图层。

## 课程

| 班级 | 描述 |
| --- | --- |
| [BlendRange](./blendrange/) | 混合范围。 |
| [ChannelInformation](./channelinformation/) | 频道信息. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | 全局图层蒙版部分。 |
| [Layer](./layer/) | psd 层。 |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | 图层混合范围数据。 |
| [LayerGroup](./layergroup/) | 组图层类 |
| [LayerHashCalculator](./layerhashcalculator/) | PSD 图层的哈希计算器。它可用于在不同的 PSD 文件中找到相同或不同的层 |
| [LayerMaskData](./layermaskdata/) | 定义基本 LayerMaskData 类，其中包含有关 PSD 文件中图层蒙版数据的信息。 它可以帮助以编程方式修改 Adobe® Photoshop® 文件并自动编辑 PSD 格式。 如果图层只有光栅蒙版，则 ImageData 包含光栅mask data bytes. 如果图层只有矢量蒙版，则 ImageData 包含矢量蒙版栅格化（缓存）数据字节。 如果图层同时具有图层和矢量蒙版，则 ImageData 包含栅格蒙版和栅格化矢量蒙版组合。 这[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)字节长度应该等于 Width * Height[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. 注意，仅删除/添加/更新 LayerMaskData 不足以正确保存 ，因为通道未更新；尽管它可能会提供正确的渲染。 [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/)方法应该用于那个. |
| [LayerMaskDataFull](./layermaskdatafull/) | 定义 LayerMaskDataFull 类，其中包含有关 PSD 文件 layer 中的蒙版数据的信息，当图层同时具有图层和矢量蒙版时。否则，一个[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) ImageData 包含光栅蒙版和光栅化矢量蒙版的组合。 ImageData 字节长度应等于 MaskRectangle.Width * MaskRectangle.Height 属性。 |
| [LayerMaskDataShort](./layermaskdatashort/) | 定义 LayerMaskDataShort 类，其中包含有关 PSD 文件 layer 中的掩码数据的信息，当图层仅具有光栅或矢量掩码而不是两者时。否则，一个[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) 如果图层只有栅格蒙版，ImageData 包含栅格蒙版数据字节。 如果图层只有矢量蒙版，ImageData 包含矢量蒙版栅格化（缓存）数据字节。 [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)字节长度应该等于 Width * Height[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/)属性. |
| [LayerResource](./layerresource/) | 表示图层信息。 |
| [LayerResourcesRegistry](./layerresourcesregistry/) | 为 PSD 文件加载定义图层资源注册表。 |
| [LinkedLayersManager](./linkedlayersmanager/) | 链接层管理器类。 |
| [SectionDividerLayer](./sectiondividerlayer/) | 用于标记文件夹（图层组）边界的部分分隔层。 |
| [TextLayer](./textlayer/) | 文字图层类 |
## 接口

| 界面 | 描述 |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | 填充设置的基本界面 |
| [ILayerResourceLoader](./ilayerresourceloader/) | 层资源加载器. |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [LayerFlags](./layerflags/) | 层 flags |
| [LayerMaskFlags](./layermaskflags/) | 图层蒙版 flags |


