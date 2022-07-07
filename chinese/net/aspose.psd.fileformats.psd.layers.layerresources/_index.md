---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Aspose.PSD for .NET API 参考
description: 命名空间包含图层中包含的 PSD 文件格式实体
type: docs
weight: 260
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/
---
命名空间包含图层中包含的 PSD 文件格式实体。

## 课程

| 班级 | 描述 |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource) | 调整图层资源的基类 |
| [AnimatedDataSectionStructure](./animateddatasectionstructure) | 带有动画数据的部分。 |
| [BlncResource](./blncresource) | BlncResource 类是颜色调整层的资源。 |
| [BlwhResource](./blwhresource) | BlwhResource 类是黑白调整层的资源。 |
| [BooleanResource](./booleanresource) | 类布尔资源。是伪资源。 Photoshop 没有吗 |
| [BritResource](./britresource) | 类 BritResource。亮度/对比度调整层资源 |
| [CgEdResource](./cgedresource) | 类 CgEdResource。内容生成器额外数据 (Photoshop CS5) |
| [ClassID](./classid) | PSD 类 ID 对象。 |
| [ClblResource](./clblresource) | 类 ClblResource。 此资源包含有关剪辑元素混合的信息。 |
| [CmlsResource](./cmlsresource) | 类 CmlsResource。 |
| [ColorRangeHsl](./colorrangehsl) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource)有 6 个颜色范围，您可以在其中更改 HSV 参数。 每个范围都有 4 个关键点来识别范围边界。它是 ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager) | 用于处理曲线的曲线调整层管理器 |
| [CurvesDiscreteManager](./curvesdiscretemanager) | 曲线调整层管理器，用于处理像素映射 |
| [CurvesManager](./curvesmanager) | 管理 CurvResource 的基类 |
| [CurvResource](./curvresource) | 类 CurvResource。曲线调整层资源 1 字节 - 如果使用曲线则为 0，如果使用地图上的像素则为 1 如果为 0，则： 2 字节 - 短。默认为 1 4 个字节 - int。仅使用最后一个字节。第一位用于 1 通道，第四位用于 4 通道，例如 2 字节 - 短点数 4 字节 * 点数 - 曲线 2 短点：第一个位置，第二个高度 4 个字节 - 单词“Crv” 2 个字节 - 对于曲线，短默认值为 4 4 个字节 - 整数。默认为 1 4 字节 - 点数 4 字节 * 点数 - 曲线 2 短的点：第一个位置，第二个高度 0-4 个字节 - 要折叠的前导四个 if 1 then： 2 个字节 - 短。默认为 1 4 个字节 - int。仅使用最后一个字节。一个通道是一位。第一位用于 1 通道，第四位用于 4 通道，例如 256 * 更改通道的计数 - 通道的有序值范围 0 - 255 4 字节 - 字“Crv” 2 个字节 - 短。对于地图上的像素，默认值为 3 4 字节 - int 通道计数 (2 + 256) 字节 - 通道索引的短 2，256 是通道的有序值，范围为 0 - 255 |
| [CustResource](./custresource) | 类 CustResource。 此资源包含有关剪辑元素混合的信息。 |
| [ExpaResource](./exparesource) | 类 ExpaResource。曝光调整层资源 |
| [FillLayerResource](./filllayerresource) | 填充层资源的基类 |
| [FilterEffectMaskData](./filtereffectmaskdata) | 过滤器掩码数据类。 |
| [FXidResource](./fxidresource) | 滤镜效果资源包含智能滤镜的通道、用户蒙版和工作表蒙版。 |
| [FxrpResource](./fxrpresource) | FxrpResource 类。层 |
| [GdFlResource](./gdflresource) | 类 GdFlResource。 此资源包含有关剪辑元素混合的信息。 |
| [Hue2Resource](./hue2resource) | 类 Hue2Resource。曝光调整层资源 |
| [InfxResource](./infxresource) | 类 InfxResource。 此资源包含有关剪辑元素混合的信息。 |
| [IopaResource](./ioparesource) | 类 IopaResource。 此资源包含有关图层样式表单中的填充不透明度属性的信息 |
| [KnkoResource](./knkoresource) | 类 KnkoResource。 此资源包含有关剪辑元素混合的信息。 |
| [LayerSectionResource](./layersectionresource) | 图层部分资源。 |
| [LclrResource](./lclrresource) | 类 LclrResource。 此资源包含有关图层列表中图层颜色的信息是 PS。只是 |
| [LevelChannel](./levelchannel) | 级别调整层中处理通道的类 |
| [LevlResource](./levlresource) | 类 LevlResource。曝光调整层资源 |
| [Lfx2Resource](./lfx2resource) | Lfx2 资源（效果资源） |
| [LiFdDataSource](./lifddatasource) | 在包含嵌入文件信息的 PSD 文件中定义 liFD 数据源类。 这是 PSD 文件格式操作 API 的一部分，有助于修改 Adobe® Photoshop® 文件 |
| [LiFeDataSource](./lifedatasource) | 定义包含外部链接文件信息的 LnkeDataSource 类。 这是 PSD File Format Manipulation API 的一部分，可帮助修改 Adobe® Photoshop® 文件 |
| [LinkDataSource](./linkdatasource) | 定义 LinkDataSource 类，该类包含有关 PSD 文件中的链接文件或资产的信息。 |
| [LinkResource](./linkresource) | 定义 LinkResource 类，该类包含有关 PSD 格式图像中链接或嵌入文件的信息。 链接资源可能包含多个[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource)实例，任何派生类中的索引器都可以访问这些实例。 |
| [Lnk2Resource](./lnk2resource) | 定义包含 PSD 格式图像中嵌入文件信息的类。 链接资源可能包含多个[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource)实例，索引器可以访问这些实例。 |
| [Lnk3Resource](./lnk3resource) | 定义包含有关嵌入文件的信息的类，该文件采用 PSD 格式（每通道 32 位图像）。 链接资源可能包含多个[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource)实例，可以由索引器访问。 |
| [LnkeResource](./lnkeresource) | 定义 LnkeResource 类，该类包含有关 PSD 格式图像中的外部链接文件或资产的信息。 链接资源可能包含多个[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource)实例，这些实例可由索引器访问。 这是 PSD 文件格式操作 API 的一部分，它有助于以编程方式修改 Adobe® Photoshop® 文件 |
| [LnsrResource](./lnsrresource) | 类 lnsrResource。 |
| [Lr16Resource](./lr16resource) | lr32 资源。 |
| [Lr32Resource](./lr32resource) | lr32 资源。 |
| [LspfResource](./lspfresource) | 图层保护设置 |
| [LuniResource](./luniresource) | 层名资源 |
| [LyidResource](./lyidresource) | 类 LyidResource。 |
| [MixrResource](./mixrresource) | 类 MixrResource。通道混合器调整层的资源 |
| [NvrtResource](./nvrtresource) | 类 NvrtResource。反转调整层的资源。 |
| [OSTypeStructure](./ostypestructure) | 表示操作系统类型结构。 |
| [OSTypeStructuresRegistry](./ostypestructuresregistry) | 表示[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)资源注册表。 |
| [PattResource](./pattresource) | 类 PattResource。带有模式数据的资源 |
| [PattResourceData](./pattresourcedata) | 用于存储[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource)资源的模式数据的类。 |
| [PhflResource](./phflresource) | PhflResource 类。曝光调整层资源 2 版本 ( = 3 ) 或 ( = 2 ) 12 XYZ 颜色各 4 个字节（仅在版本 3 中） 10 后跟 2 个字节的颜色空间由 4 * 2 字节颜色分量（仅在版本 2 中） 4 密度 1 保留亮度 |
| [PhflResourceVersion2](./phflresourceversion2) | PhflResource 类。曝光调整层资源 2 版本 ( = 3 ) 或 ( = 2 ) 12 XYZ 颜色各 4 个字节（仅在版本 3 中） 10 后跟 2 个字节的颜色空间由 4 * 2 字节颜色分量（仅在版本 2 中） 4 密度 1 保留亮度 |
| [PhflResourceVersion3](./phflresourceversion3) | PhflResource 类。曝光调整层资源 2 版本 ( = 3 ) 或 ( = 2 ) 12 XYZ 颜色各 4 个字节（仅在版本 3 中） 10 后跟 2 个字节的颜色空间由 4 * 2 字节颜色分量（仅在版本 2 中） 4 密度 1 保留亮度 |
| [PlacedResource](./placedresource) | 定义 PlacedResource 类，该类包含有关 PSD 文件中已放置层或智能对象层的通用信息。 用于支持 Adobe® Photoshop® 图像中的智能对象层。 |
| [PlLdResource](./plldresource) | 定义 PlLdResource 类，该类包含有关 PSD 文件中放置层的信息。 用于支持 Adobe® Photoshop® 图像中的智能对象层。 在 Adobe® Photoshop® CS3 中被 SoLdResource 取代 |
| [PtFlResource](./ptflresource) | 类 PtFlResource。包含图案填充图层数据。 |
| [ShmdResource](./shmdresource) | 类 ShmdResource。元数据设置 |
| [SmartObjectResource](./smartobjectresource) | 定义 SmartObjectResource 类，该类包含有关 PSD 文件中智能对象层的信息。 Is 是 Sold 和 Sole 资源的基类，用于支持 Adobe® Photoshop® 图像中的智能对象层。 |
| [SmartResourceCreator](./smartresourcecreator) | 定义可以创建 PlLd、SoLd 和 SoLe 资源的 SmartResourceCreator 类。 用于支持 Adobe® Photoshop® 图像中的智能对象层。 |
| [SoCoResource](./socoresource) | 类 SoCoResource。 此资源包含有关颜色填充层的信息 |
| [SoLdResource](./soldresource) | 定义包含有关 PSD 文件中智能对象层信息的 SoLdResource 类。 用于支持 Adobe® Photoshop® 图像中的智能对象层。 |
| [SoLeResource](./soleresource) | 定义包含有关 PSD 文件中智能对象层信息的 SoLeResource 类。 用于支持 Adobe® Photoshop® 图像中带有外部文件链接的智能对象层。 |
| [Txt2Resource](./txt2resource) | Txt2 资源类 |
| [TypeToolFontInfo](./typetoolfontinfo) | 包含有关文字工具字体的信息。 |
| [TypeToolInfo6Resource](./typetoolinfo6resource) | 类型工具信息。对于高于或等于 6.0 的 PSD 版本。 |
| [TypeToolInfoResource](./typetoolinforesource) | 类型工具信息。对于低于 6.0 的 PSD 版本。 |
| [TypeToolLineInfo](./typetoollineinfo) | 键入工具线信息。 |
| [TypeToolStyleInfo](./typetoolstyleinfo) | 键入工具样式信息。 |
| [UnknownResource](./unknownresource) | 未知资源。 |
| [VectorPathDataResource](./vectorpathdataresource) | 类 VectorPathDataResource。 此资源包含有关矢量图层蒙版的信息 |
| [VibAResource](./vibaresource) | VibA 资源。 |
| [VmskResource](./vmskresource) | 类 VmskResource。 此资源包含有关矢量图层蒙版的信息 |
| [VogkResource](./vogkresource) | 向量起始数据资源。 |
| [VsmsResource](./vsmsresource) | 类 VsmsResource。 此资源包含有关矢量图层蒙版的信息 |
## 接口

| 界面 | 描述 |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader) | [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)资源加载器。 |
| [IPlacedLayerResource](./iplacedlayerresource) | 定义 IPlacedLayerResource 接口，该接口包含有关 PSD 文件中放置层的信息。 是一个标记界面，用于在 Adobe® Photoshop® 图像中指定 PlLd、Sold 和 Sole 资源。 用于支持 Adobe® Photoshop® 图像中的智能对象层。 |
| [ISmartObjectLayerResource](./ismartobjectlayerresource) | 定义 ISmartObjectLayerResource 接口，该接口包含有关 PSD 文件中智能对象层资源的信息。 也是一个标记界面，用于在 Adobe® Photoshop® 图像中指定 Sold 和 Sole 资源。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [LayerLockType](./layerlocktype) | 层锁定选项 |
| [LayerSectionSubtype](./layersectionsubtype) | 部分子类型 |
| [LayerSectionType](./layersectiontype) | 图层截面类型 |
| [LinkDataSourceType](./linkdatasourcetype) | 为 PSD 链接资源中的数据源定义 LinkDataSourceType 枚举。 |
| [LnsrResourceType](./lnsrresourcetype) | 发现可能的 Lnsr 资源类型 |
| [PlacedLayerType](./placedlayertype) | 定义放置层 PlLd 资源的 PlacedLayerType 枚举。 |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum) | Sheet 颜色设置的可能颜色。 PS 中图层列表中图层的 UI 装饰颜色 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
