---
title: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources"
second_title: "Aspose.PSD for .NET API 参考"
description: "该命名空间包含位于图层中的 PSD 文件格式实体"
type: docs
weight: 300
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/
---
{{< psd/tize >}}
该命名空间包含位于图层中的 PSD 文件格式实体。

## 类

| 类 | 描述 |
| --- | --- |
| [AbddResource](./abddresource/) | 画板信息数据。 |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | 调整图层资源的基类 |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | 包含动画数据的部分。 |
| [ArtBResource](./artbresource/) | 用于[`Resources`](../aspose.psd.fileformats.psd.layers/layer/resources/)的画板信息数据。 |
| [ArtDResource](./artdresource/) | 用于[`GlobalLayerResources`](../aspose.psd.fileformats.psd/psdimage/globallayerresources/)的画板信息数据。 |
| [BaseArtboardInfoResource](./baseartboardinforesource/) | 画板信息数据资源。 |
| [BaseFxResource](./basefxresource/) | 基础效果资源 |
| [BaseLayerSectionResource](./baselayersectionresource/) | 图层部分资源的基类 |
| [BlncResource](./blncresource/) | BlncResource 类是颜色调整图层的资源。 |
| [BlwhResource](./blwhresource/) | BlwhResource 类是黑白调整图层的资源。 |
| [BooleanResource](./booleanresource/) | BooleanResource 类。它是伪资源。Photoshop 没有此资源。 |
| [BritResource](./britresource/) | BritResource 类。亮度/对比度调整图层的资源 |
| [CgEdResource](./cgedresource/) | CgEdResource 类。内容生成器额外数据（Photoshop CS5） |
| [ClassID](./classid/) | PSD 类 ID 对象。 |
| [ClblResource](./clblresource/) | ClblResource 类。此资源包含有关剪切元素混合的信息。 |
| [CmlsResource](./cmlsresource/) | CmlsResource 类。 |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) 有 6 个颜色范围，可在其中更改 HSV 参数。每个范围有 4 个关键点用于标识范围边界。这是 ColorRangeHsl。 |
| [CurvesContinuousManager](./curvescontinuousmanager/) | 曲线调整图层的管理器，用于操作曲线 |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | 曲线调整图层的管理器，用于操作像素映射 |
| [CurvesManager](./curvesmanager/) | 管理 CurvResource 的基类 |
| [CurvResource](./curvresource/) | CurvResource 类。曲线调整图层的资源 1 字节 - 0 表示使用曲线，1 表示在映射上使用像素；如果为 0，则：2 字节 - short，默认值为 1；4 字节 - int，仅使用最后一个字节的位。第一位对应 1 通道，第四位对应 4 通道，例如 2 字节 - short 表示点数，4 字节 * 点数 - 曲线的点，2 short：第一个位置，第二个高度；4 字节 - word "Crv "；2 字节 - short，默认值为 4（用于曲线）；4 字节 - int，默认值为 1；4 字节 - 点数，4 字节 * 点数 - 曲线的点，2 short：第一个位置，第二个高度；0-4 字节 - 用于四个通道的折叠，如果为 1，则：2 字节 - short，默认值为 1；4 字节 - int，仅使用最后一个字节。一个通道占用一位。第一位对应 1 通道，第四位对应 4 通道，例如 256 * 改变的通道数 - 按顺序的通道值，范围 0 - 255；4 字节 - word "Crv "；2 字节 - short，默认值为 3（用于映射上的像素）；4 字节 - int 通道计数 (2 + 256) 字节 - short，2 表示通道索引，256 为范围 0 - 255 的有序通道值。 |
| [CustResource](./custresource/) | CustResource 类。此资源包含有关剪切元素混合的信息。 |
| [ExpaResource](./exparesource/) | 类 ExpaResource。曝光调整图层的资源 |
| [FillLayerResource](./filllayerresource/) | 填充图层资源的基类。 |
| [FilterEffectMaskData](./filtereffectmaskdata/) | 滤镜蒙版数据类。 |
| [FXidResource](./fxidresource/) | 滤镜效果资源包含通道、用户蒙版和智能滤镜的工作表蒙版。 |
| [FxrpResource](./fxrpresource/) | 类 FxrpResource。图层的参考点 |
| [GdFlResource](./gdflresource/) | 类 GdFlResource。此资源包含有关剪切元素混合的信息。 |
| [GrdmResource](./grdmresource/) | 类 GrdmResource。包含有关渐变映射图层的信息。 |
| [Hue2Resource](./hue2resource/) | 类 Hue2Resource。曝光调整图层的资源 |
| [IfxsResource](./ifxsresource/) | Ifxs 资源（组图层效果资源） |
| [ImfxResource](./imfxresource/) | Imfx 资源（多重效果资源） |
| [InfxResource](./infxresource/) | 类 InfxResource。此资源包含有关剪切元素混合的信息。 |
| [IopaResource](./ioparesource/) | 类 IopaResource。此资源包含来自图层样式表单的填充不透明度属性信息 |
| [KnkoResource](./knkoresource/) | 类 KnkoResource。此资源包含有关剪切元素混合的信息。 |
| [LayerSectionResource](./layersectionresource/) | 图层节资源。 |
| [LclrResource](./lclrresource/) | 类 LclrResource。此资源包含关于 PS 中图层列表中图层颜色的信息。仅此 |
| [LevelChannel](./levelchannel/) | 用于在色阶调整图层中处理通道的类 |
| [LevlResource](./levlresource/) | 类 LevlResource。曝光调整图层的资源 |
| [Lfx2Resource](./lfx2resource/) | Lfx2 资源（常规效果资源） |
| [LiFdDataSource](./lifddatasource/) | 定义 PSD 文件中 liFD 数据源类，包含有关嵌入文件的信息。这是 PSD 文件格式操作 API 的一部分，帮助修改 Adobe® Photoshop® 文件 |
| [LiFeDataSource](./lifedatasource/) | 定义 LnkeDataSource 类，包含有关外部链接文件的信息。这是 PSD 文件格式操作 API 的一部分，帮助修改 Adobe® Photoshop® 文件 |
| [LinkDataSource](./linkdatasource/) | 定义 LinkDataSource 类，包含有关 PSD 文件中链接文件或资产的信息。 |
| [LinkResource](./linkresource/) | 定义 LinkResource 类，包含有关 PSD 格式图像中链接或嵌入文件的信息。该链接资源可能包含多个 [`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) 实例，可通过任何派生类中的索引器访问。 |
| [LmskResource](./lmskresource/) | LMsk 资源。 |
| [Lnk2Resource](./lnk2resource/) | 定义包含 PSD 格式图像中嵌入文件信息的类。该链接资源可能包含多个 [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) 实例，可通过索引器访问。 |
| [Lnk3Resource](./lnk3resource/) | 定义包含 PSD 格式每通道 32 位图像中嵌入文件信息的类。该链接资源可能包含多个 [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) 实例，可通过索引器访问。 |
| [LnkeResource](./lnkeresource/) | 定义 LnkeResource 类，该类包含有关 PSD 格式图像中外部链接文件或资源的信息。链接资源可能包含多个 [`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 实例，可通过索引器访问。这是 PSD 文件格式操作 API 的一部分，帮助以编程方式修改 Adobe® Photoshop® 文件。 |
| [LnsrResource](./lnsrresource/) | 类 lnsrResource。 |
| [Lr16Resource](./lr16resource/) | lr16 资源。 |
| [Lr32Resource](./lr32resource/) | lr32 资源。 |
| [LrXxResource](./lrxxresource/) | lrXX 资源。 |
| [LsdkResource](./lsdkresource/) | lsdk 图层资源（嵌套图层部分资源）。 |
| [LspfResource](./lspfresource/) | 图层受保护设置 |
| [LuniResource](./luniresource/) | 图层名称资源 |
| [LyidResource](./lyidresource/) | 类 LyidResource。 |
| [LyvrResource](./lyvrresource/) | 用于表示图层的 Photoshop 版本的资源。 |
| [MixrResource](./mixrresource/) | 类 MixrResource。通道混合器调整图层的资源 |
| [MlstResource](./mlstresource/) | mlst 资源。此类除其他功能外，还包含有关图层在时间轴上位置的信息。 |
| [NvrtResource](./nvrtresource/) | 类 NvrtResource。反相调整图层的资源。 |
| [OSTypeStructure](./ostypestructure/) | 表示 OS 类型结构。 |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | 表示 [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 资源注册表。 |
| [PathShape](./pathshape/) | 贝塞尔曲线节点处的图形。 |
| [PattResource](./pattresource/) | 类 PattResource。包含图案数据的资源 |
| [PattResourceData](./pattresourcedata/) | 用于存储 [`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 资源的图案数据的类。 |
| [PhflResource](./phflresource/) | 类 PhflResource。曝光调整图层的资源，版本 2（= 3）或（= 2），每个 XYZ 颜色占 12 4 字节（仅在版本 3 中），颜色空间占 10 2 字节，随后是 4 * 2 字节的颜色分量（仅在版本 2 中），密度 4，保留亮度 1。 |
| [PhflResourceVersion2](./phflresourceversion2/) | 类 PhflResource。曝光调整图层的资源，版本 2（= 3）或（= 2），每个 XYZ 颜色占 12 4 字节（仅在版本 3 中），颜色空间占 10 2 字节，随后是 4 * 2 字节的颜色分量（仅在版本 2 中），密度 4，保留亮度 1。 |
| [PhflResourceVersion3](./phflresourceversion3/) | 类 PhflResource。曝光调整图层的资源，版本 2（= 3）或（= 2），每个 XYZ 颜色占 12 4 字节（仅在版本 3 中），颜色空间占 10 2 字节，随后是 4 * 2 字节的颜色分量（仅在版本 2 中），密度 4，保留亮度 1。 |
| [PlacedResource](./placedresource/) | 定义 PlacedResource 类，该类包含 PSD 文件中已放置图层或智能对象图层的通用信息。用于在 Adobe� Photoshop� 图像中支持智能对象图层。 |
| [PlLdResource](./plldresource/) | 定义 PlLdResource 类，该类包含 PSD 文件中已放置图层的信息。用于在 Adobe� Photoshop� 图像中支持智能对象图层。它已在 Adobe� Photoshop� CS3 中被 SoLdResource 替代。 |
| [PostResource](./postresource/) | 类 PostResource。色调分离图层设置。 |
| [PtFlResource](./ptflresource/) | 类 PtFlResource。包含图案填充图层数据。 |
| [ShmdResource](./shmdresource/) | 类 ShmdResource。元数据设置 |
| [SmartObjectResource](./smartobjectresource/) | 定义 SmartObjectResource 类，该类包含 PSD 文件中智能对象图层的信息。它是 Sold 和 Sole 资源的基类，用于在 Adobe� Photoshop� 图像中支持智能对象图层。 |
| [SmartResourceCreator](./smartresourcecreator/) | 定义 SmartResourceCreator 类，可创建 PlLd、SoLd 和 SoLe 资源。用于在 Adobe® Photoshop® 图像中支持智能对象图层。 |
| [SoCoResource](./socoresource/) | 类 SoCoResource。此资源包含有关颜色填充图层的信息 |
| [SoLdResource](./soldresource/) | 定义 SoLdResource 类，包含有关 PSD 文件中智能对象图层的信息。用于在 Adobe® Photoshop® 图像中支持智能对象图层。 |
| [SoLeResource](./soleresource/) | 定义 SoLeResource 类，包含有关 PSD 文件中智能对象图层的信息。用于在 Adobe® Photoshop® 图像中支持带外部文件链接的智能对象图层。 |
| [Txt2Resource](./txt2resource/) | Txt2 资源类 |
| [TypeToolFontInfo](./typetoolfontinfo/) | 包含有关文字工具字体的信息。 |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | 文字工具信息。适用于 PSD 版本大于或等于 6.0 的情况。 |
| [TypeToolInfoResource](./typetoolinforesource/) | 文字工具信息。适用于 PSD 版本低于 6.0 的情况。 |
| [TypeToolLineInfo](./typetoollineinfo/) | 文字工具线条信息。 |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | 文字工具样式信息。 |
| [UnknownResource](./unknownresource/) | 未知资源。 |
| [VectorPath](./vectorpath/) | 包含矢量路径的类。 |
| [VectorPathDataResource](./vectorpathdataresource/) | 类 VectorPathDataResource。此资源包含有关矢量图层蒙版的信息。 |
| [VibAResource](./vibaresource/) | VibA 资源。 |
| [VmskResource](./vmskresource/) | 类 VmskResource。此资源包含有关矢量图层蒙版的信息。 |
| [VogkResource](./vogkresource/) | 矢量起始数据资源。 |
| [VsmsResource](./vsmsresource/) | 类 VsmsResource。此资源包含有关矢量图层蒙版的信息。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 资源加载器。 |
| [IPath](./ipath/) | 接口描述了形状图层中存在的路径集合。 |
| [IPathShape](./ipathshape/) | 贝塞尔曲线节点形成的形状。 |
| [IPlacedLayerResource](./iplacedlayerresource/) | 定义 IPlacedLayerResource 接口，包含有关 PSD 文件中已放置图层的信息。它是用于在 Adobe® Photoshop® 图像中标记 PlLd、Sold 和 Sole 资源的标记接口。用于在 Adobe® Photoshop® 图像中支持智能对象图层。 |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | 定义 ISmartObjectLayerResource 接口，包含有关 PSD 文件中智能对象图层资源的信息。它也是用于在 Adobe® Photoshop® 图像中标记 Sold 和 Sole 资源的标记接口。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [LayerLockType](./layerlocktype/) | 图层锁定选项 |
| [LayerSectionSubtype](./layersectionsubtype/) | 分区子类型 |
| [LayerSectionType](./layersectiontype/) | 图层分区类型 |
| [LinkDataSourceType](./linkdatasourcetype/) | 定义 PSD 链接资源中数据源的 LinkDataSourceType 枚举。 |
| [LnsrResourceType](./lnsrresourcetype/) | 已发现可能的 Lnsr 资源类型 |
| [PlacedLayerType](./placedlayertype/) | 定义已放置图层 PlLd 资源的 PlacedLayerType 枚举。 |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | Sheet 颜色设置的可能颜色。它是 PS 中图层列表的 UI 装饰颜色。 |


