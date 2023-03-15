---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Aspose.PSD for .NET API 参考
description: 命名空间包含图层中包含的 PSD 文件格式实体
type: docs
weight: 270
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/
---
命名空间包含图层中包含的 PSD 文件格式实体。

## 课程

| 班级 | 描述 |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | 调整图层资源的基类 |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | 带有动画数据的部分。 |
| [BlncResource](./blncresource/) | BlncResource类是Color Adjustment Layer的资源。 |
| [BlwhResource](./blwhresource/) | BlwhResource类是黑白调整层的资源。 |
| [BooleanResource](./booleanresource/) | 类布尔资源。这是伪资源。 Photoshop 没有 |
| [BritResource](./britresource/) | 类 BritResource。亮度/对比度调整图层资源 |
| [CgEdResource](./cgedresource/) | 类 CgEdResource。内容生成器额外数据 (Photoshop CS5) |
| [ClassID](./classid/) | PSD 类 ID 对象。 |
| [ClblResource](./clblresource/) | ClblResource 类。 此资源包含有关剪切元素混合的信息。 |
| [CmlsResource](./cmlsresource/) | 类 CmlsResource. |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/)有 6 个颜色范围，您可以在其中更改 HSV 参数。 每个范围都有 4 个关键点来标识范围边界。它是 ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager/) | 操纵曲线的曲线调整图层管理器 |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | 曲线调整图层管理器，用于操作像素的 map |
| [CurvesManager](./curvesmanager/) | 管理 CurvResource 的基类 |
| [CurvResource](./curvresource/) | 类 CurvResource。曲线调整图层资源 1 字节 - 如果使用曲线则为 0，如果使用地图上的像素则为 1 如果为 0 则： 2 字节 - 短。默认为 1 4 字节 - int。仅使用最后一个字节。第一位用于 1 通道，第四位用于 4 通道，例如 2 字节 - 短点 count 4 字节 * 点数 - 曲线点 2 短：第一个位置，第二个高度 4 字节 - 字“Crv” 2 字节 - Curves 4 字节的短默认值为 4 - int。默认为 1 4 字节 - 点计数 4 字节 * 点计数 - 曲线 2 短的点：第一个位置，第二个高度 0-4 字节 - 导致折叠 four if 1 then: 2 字节 - 短。默认为 1 4 字节 - int。仅使用最后一个字节。一个通道是一位。第一位用于 1 个通道，第四位用于 4 个通道，例如 256 * 更改通道的计数 - 范围为 0 - 255 4 字节的通道的有序值 - 字“Crv” 2 字节 - 短。 map 上的像素默认值为 3 4 字节 - int Channel count (2 + 256) 字节 - 通道索引的短 2，256 是通道在 0 - 255 范围内的有序值 |
| [CustResource](./custresource/) | CustResource 类。 此资源包含有关剪切元素混合的信息。 |
| [ExpaResource](./exparesource/) | 类 ExpaResource。曝光调整图层资源 |
| [FillLayerResource](./filllayerresource/) | 填充层资源的基类 |
| [FilterEffectMaskData](./filtereffectmaskdata/) | 过滤器掩码数据类。 |
| [FXidResource](./fxidresource/) | 滤镜效果资源包含通道、用户蒙版和智能滤镜的工作表蒙版。 |
| [FxrpResource](./fxrpresource/) | 类 FxrpResource。 layer 的参考点 |
| [GdFlResource](./gdflresource/) | GdFlResource 类。 此资源包含有关剪切元素混合的信息。 |
| [Hue2Resource](./hue2resource/) | 类 Hue2Resource。曝光调整图层资源 |
| [InfxResource](./infxresource/) | InfxResource 类。 此资源包含有关剪切元素混合的信息。 |
| [IopaResource](./ioparesource/) | Class IopaResource. 此资源包含有关图层样式 form 的填充不透明度属性的信息 |
| [KnkoResource](./knkoresource/) | KnkoResource 类。 此资源包含有关剪切元素混合的信息。 |
| [LayerSectionResource](./layersectionresource/) | 图层部分资源。 |
| [LclrResource](./lclrresource/) | Class LclrResource. 此资源包含有关图层列表中图层颜色的信息是 PS。这只是 |
| [LevelChannel](./levelchannel/) | 用于在 Levels Adjustment Layer 中处理通道的类 |
| [LevlResource](./levlresource/) | 类 LevlResource。曝光调整图层资源 |
| [Lfx2Resource](./lfx2resource/) | Lfx2 资源（效果资源） |
| [LiFdDataSource](./lifddatasource/) | 在 PSD 文件中定义 liFD 数据源类，其中包含有关嵌入文件的信息。 这是 PSD 文件格式操作 API 的一部分，有助于修改 Adobe® Photoshop® 文件 |
| [LiFeDataSource](./lifedatasource/) | 定义包含有关外部链接文件的信息的 LnkeDataSource 类。 这是 PSD 文件格式操作 API 的一部分，有助于修改 Adobe® Photoshop® 文件 |
| [LinkDataSource](./linkdatasource/) | 定义 LinkDataSource 类，其中包含有关链接文件或 PSD 文件中资产的信息。 |
| [LinkResource](./linkresource/) | 定义 LinkResource 类，其中包含有关 PSD 格式图像中链接或嵌入文件的信息。 链接资源可能包含几个[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)任何派生类中的索引器都可以访问的实例。 |
| [Lnk2Resource](./lnk2resource/) | 定义包含有关 PSD 格式图像中嵌入文件信息的类。 链接资源可能包含多个[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/)索引器可以访问的实例. |
| [Lnk3Resource](./lnk3resource/) | 定义包含 PSD 格式 32 位每通道图像的嵌入文件信息的类。 链接资源可能包含多个[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/)indexer. 可以访问的实例 |
| [LnkeResource](./lnkeresource/) | 定义 LnkeResource 类，其中包含 PSD 格式图像中有关外部链接文件或资产的信息。 链接资源可能包含几个[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/)索引器可以访问的实例。 这是 PSD 文件格式操作 API 的一部分，有助于以编程方式修改 Adobe® Photoshop® 文件 |
| [LnsrResource](./lnsrresource/) | 类 lnsrResource. |
| [Lr16Resource](./lr16resource/) | lr32 资源。 |
| [Lr32Resource](./lr32resource/) | lr32 资源。 |
| [LspfResource](./lspfresource/) | 层保护设置 |
| [LuniResource](./luniresource/) | 图层名称 resource |
| [LyidResource](./lyidresource/) | 类 LyidResource. |
| [MixrResource](./mixrresource/) | 类 MixrResource。 Channel Mixer Adjustment Layer资源 |
| [MlstResource](./mlstresource/) | mlst 资源。 这个类，除其他外，包含有关层在时间轴上的位置的信息。 |
| [NvrtResource](./nvrtresource/) | 类 NvrtResource。反转调整图层资源. |
| [OSTypeStructure](./ostypestructure/) | 表示OS类型结构。 |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | 代表[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)资源注册表. |
| [PattResource](./pattresource/) | 类 PattResource。具有模式 data 的资源 |
| [PattResourceData](./pattresourcedata/) | 存储模式数据的类[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/)资源. |
| [PhflResource](./phflresource/) | PhflResource 类。 Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2) 4 密度 1 保持亮度 |
| [PhflResourceVersion2](./phflresourceversion2/) | PhflResource 类。 Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2) 4 密度 1 保持亮度 |
| [PhflResourceVersion3](./phflresourceversion3/) | PhflResource 类。 Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2) 4 密度 1 保持亮度 |
| [PlacedResource](./placedresource/) | 定义 PlacedResource 类，其中包含有关 PSD 文件中放置层或智能对象层的公共信息。 用于支持 Adobe® Photoshop® 图像中的智能对象层。 |
| [PlLdResource](./plldresource/) | 定义 PlLdResource 类，其中包含有关 PSD 文件中已放置层的信息。 用于支持 Adobe® Photoshop® 图像中的智能对象层。 在 Adobe® Photoshop® CS3 中已被 SoLdResource 取代 |
| [PostResource](./postresource/) | 类 PostResource。色调分离层设置. |
| [PtFlResource](./ptflresource/) | 类 PtFlResource。包含图案填充图层数据。 |
| [ShmdResource](./shmdresource/) | 类 ShmdResource。元数据设置 |
| [SmartObjectResource](./smartobjectresource/) | 定义 SmartObjectResource 类，其中包含有关 PSD 文件中智能对象层的信息。 是用于支持 Adobe® Photoshop® 图像中的智能对象层的 Sold 和 Sole 资源的基类。 |
| [SmartResourceCreator](./smartresourcecreator/) | 定义可以创建 PlLd、SoLd 和 SoLe 资源的 SmartResourceCreator 类。 用于支持 Adobe® Photoshop® 图像中的智能对象层。 |
| [SoCoResource](./socoresource/) | 类 SoCoResource. 此资源包含有关 Color Fill Layers 的信息 |
| [SoLdResource](./soldresource/) | 定义 SoLdResource 类，其中包含有关 PSD 文件中智能对象层的信息。 用于支持 Adobe® Photoshop® 图像中的智能对象层。 |
| [SoLeResource](./soleresource/) | 定义 SoLeResource 类，其中包含有关 PSD 文件中智能对象层的信息。 用于支持 Adobe® Photoshop® 图像中具有外部文件链接的智能对象层。 |
| [Txt2Resource](./txt2resource/) | Txt2 资源类 |
| [TypeToolFontInfo](./typetoolfontinfo/) | 包含有关文字工具字体的信息。 |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | 类型工具信息。对于高于或等于 6.0. 的 PSD 版本 |
| [TypeToolInfoResource](./typetoolinforesource/) | 类型工具信息。对于低于 6.0. 的 PSD 版本 |
| [TypeToolLineInfo](./typetoollineinfo/) | 类型工具行信息。 |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | 键入工具样式信息。 |
| [UnknownResource](./unknownresource/) | 未知资源。 |
| [VectorPathDataResource](./vectorpathdataresource/) | Class VectorPathDataResource. 此资源包含有关矢量图层掩码 的信息 |
| [VibAResource](./vibaresource/) | VibA 资源. |
| [VmskResource](./vmskresource/) | Class VmskResource. 此资源包含有关向量层掩码 的信息 |
| [VogkResource](./vogkresource/) | Vector Origination Data 资源。 |
| [VsmsResource](./vsmsresource/) | Class VsmsResource. 此资源包含有关矢量图层掩码 的信息 |
## 接口

| 界面 | 描述 |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | 的[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)资源加载器. |
| [IPlacedLayerResource](./iplacedlayerresource/) | 定义 IPlacedLayerResource 接口，其中包含有关 PSD 文件中已放置层的信息。 是一个标记接口，用于指定 Adobe® Photoshop® 图像中的 PlLd、Sold 和 Sole 资源。 is 用于支持智能对象层Adobe® Photoshop® 图像. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | 定义 ISmartObjectLayerResource 接口，其中包含有关 PSD 文件中的智能对象层资源的信息。 也是一个标记接口，用于在 Adobe® Photoshop® 图像中指定 Sold 和 Sole 资源。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [LayerLockType](./layerlocktype/) | 图层锁定选项 |
| [LayerSectionSubtype](./layersectionsubtype/) | 部分 subtype |
| [LayerSectionType](./layersectiontype/) | 层段类型 |
| [LinkDataSourceType](./linkdatasourcetype/) | 为 PSD 链接资源中的数据源定义 LinkDataSourceType 枚举。 |
| [LnsrResourceType](./lnsrresourcetype/) | 发现可能的 Lnsr 资源类型 |
| [PlacedLayerType](./placedlayertype/) | 为放置层 PlLd 资源定义 PlacedLayerType 枚举。 |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | Sheet颜色设置的可能颜色。 PS 图层列表中图层的UI装饰色 |


