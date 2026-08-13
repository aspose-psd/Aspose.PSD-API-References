---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /zh/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **类** | **Description** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | 画板图层类。 |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | 混合范围。 |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | 通道信息。 |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | 全局图层蒙版部分。 |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | 基础填充设置接口 |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | 层资源加载器。 |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | 描述 Shape 图层的属性。 |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | psd 图层。 |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | 图层混合范围数据。 |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | 组图层类 |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | PSD 图层的哈希计算器。可用于在不同的 PSD 文件中查找相同或不同的图层。 |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | 定义基类 LayerMaskData 类，其中包含 PSD 文件中图层蒙版数据的信息。<br/>            它可以帮助以编程方式修改 Adobe® Photoshop® 文件并自动化 PSD 格式编辑。<br/>            如果图层仅有光栅蒙版，则 ImageData 包含光栅蒙版数据字节。<br/>            如果图层仅有矢量蒙版，则 ImageData 包含矢量蒙版的光栅化（缓存）数据字节。<br/>            如果图层同时拥有图层蒙版和矢量蒙版，则 ImageData 包含光栅蒙版和光栅化的矢量蒙版的组合。<br/>            [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) 字节长度应等于 [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) 属性的 Width * Height。<br/>            请注意，仅删除/添加/更新 LayerMaskData 并不足以正确保存，因为通道未更新；尽管可能提供正确的渲染。<br/>            应使用 [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 方法来完成此操作。 |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | 定义 LayerMaskDataFull 类，其中包含 PSD 文件图层中蒙版数据的信息<br/>            当图层同时拥有图层蒙版和矢量蒙版时。否则，使用 [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/)。<br/>            ImageData 包含光栅蒙版和光栅化的矢量蒙版的组合。<br/>            ImageData 的字节长度应等于 MaskRectangle.Width * MaskRectangle.Height 属性。 |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | 定义 LayerMaskDataShort 类，其中包含 PSD 文件图层中蒙版数据的信息<br/>            当图层仅有光栅蒙版或矢量蒙版但不同时拥有两者时。否则，使用 [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/)。<br/>            如果图层仅有光栅蒙版，则 ImageData 包含光栅蒙版数据字节。<br/>            如果图层仅有矢量蒙版，则 ImageData 包含矢量蒙版的光栅化（缓存）数据字节。<br/>            [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) 的字节长度应等于 [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) 属性的 Width * Height。 |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | 表示图层信息。 |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | 定义 PSD 文件加载的图层资源注册表。 |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | 链接图层管理器类。 |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | 用于标记文件夹（图层组）边界的分段分隔图层。 |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | 形状图层。封装了对形状图层及相关资源的操作逻辑。 |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | 文本图层类 |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | 图层标志 |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | 图层蒙版标志 |
