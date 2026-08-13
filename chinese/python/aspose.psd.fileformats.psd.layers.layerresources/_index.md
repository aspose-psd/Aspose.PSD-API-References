---
title: "aspose.psd.fileformats.psd.layers.layerresources"
type: docs
weight: 330
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/
---




## **Classes**
| **类** | **Description** |
| :- | :- |
| [AbddResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/abddresource/) | 画板信息数据。 |
| [AdjustmentLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/) | 调整图层资源的基类 |
| [AnimatedDataSectionStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/) | 包含动画数据的部分。 |
| [ArtBResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) | 画板信息数据用于 [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/)。 |
| [ArtDResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artdresource/) | 画板信息数据用于 [PsdImage.global_layer_resources](/psd/python-net/aspose.psd.fileformats.psd/psdimage/)。 |
| [BaseArtboardInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/) | 画板信息数据资源。 |
| [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) | BlncResource 类是颜色调整图层的资源。 |
| [BlwhResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/) | BlwhResource 类是黑白调整图层的资源。 |
| [BooleanResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/booleanresource/) | BooleanResource 类。它是伪资源。Photoshop 没有它 |
| [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) | BritResource 类。亮度/对比度调整图层的资源。 |
| [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) | CgEdResource 类。内容生成器额外数据（Photoshop CS5） |
| [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid/) | PSD 类 ID 对象。 |
| [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) | ClblResource 类。<br/>            此资源包含有关剪切元素混合的信息。 |
| [CmlsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cmlsresource/) | CmlsResource 类。 |
| [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) | [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) 有 6 个颜色范围，可更改 HSV 参数。<br/>            每个范围有 4 个关键点用于标识范围边界。这是 ColorRangeHsl |
| [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) | CurvResource 类。曲线调整图层的资源<br/>            1 字节 - 如果使用曲线为 0，使用像素映射为 1<br/>            如果为 0，则：<br/>            2 字节 - short。默认值为 1<br/>            4 字节 - int。仅使用最后一个字节的位。第一位表示 1 通道，第四位表示 4 通道，例如<br/>            2 字节 - short 点计数<br/>            4 字节 * 点数 - 曲线点 2 short：第一个位置，第二个高度<br/>            4 字节 - word "Crv "<br/>            2 字节 - short，默认值为 4（用于曲线）<br/>            4 字节 - int。默认值为 1<br/>            4 字节 - 点计数<br/>            4 字节 * 点计数 - 曲线点 2 short：第一个位置，第二个高度<br/>            0-4 字节 - 为四个折叠的前导<br/>            如果为 1，则：<br/>            2 字节 - short。默认值为 1<br/>            4 字节 - int。仅使用最后一个字节。一个通道占一位。第一位表示 1 通道，第四位表示 4 通道，例如<br/>            256 * 变更通道数 - 通道在 0-255 范围内的有序值<br/>            4 字节 - word "Crv "<br/>            2 字节 - short。默认值为 3（用于像素映射）<br/>            4 字节 - int 通道计数<br/>            (2 + 256) 字节 - short 2 用于通道索引，256 为通道在 0-255 范围内的有序值 |
| [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) | 用于操作曲线的曲线调整图层管理器 |
| [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) | 用于操作像素映射的曲线调整图层管理器 |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager/) | 用于管理 CurvResource 的基类 |
| [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) | 类 CustResource。<br/>            此资源包含有关剪切元素混合的信息。 |
| [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) | 类 ExpaResource。曝光调整图层的资源 |
| [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) | Filter Effects 资源包含通道、用户蒙版和用于智能滤镜的工作表蒙版。 |
| [FillLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filllayerresource/) | 用于填充图层资源的基类。 |
| [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) | 过滤蒙版数据类。 |
| [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) | 类 FxrpResource。图层的参考点 |
| [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) | 类 GdFlResource。<br/>            此资源包含有关剪切元素混合的信息。 |
| [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) | 类 GrdmResource。包含有关 Gradient-Map 图层的信息。 |
| [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) | 类 Hue2Resource。曝光调整图层的资源 |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/) | 该 [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 资源加载器。 |
| [IPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipath/) | 接口描述了呈现在形状图层中的路径集合。 |
| [IPathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/) | 来自贝塞尔曲线节点的形状。 |
| [IPlacedLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/) | 定义 IPlacedLayerResource 接口，该接口包含 PSD 文件中已放置图层的信息。<br/>            这是用于在 Adobe® Photoshop® 图像中指定 PlLd、Sold 和 Sole 资源的标记接口。<br/>            用于在 Adobe® Photoshop® 图像中支持智能对象图层。 |
| [ISmartObjectLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/) | 定义 ISmartObjectLayerResource 接口，该接口包含 PSD 文件中智能对象图层资源的信息。<br/>            这也是用于在 Adobe® Photoshop® 图像中指定 Sold 和 Sole 资源的标记接口。 |
| [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) | 类 InfxResource。<br/>            此资源包含有关剪切元素混合的信息。 |
| [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) | 类 IopaResource。<br/>            此资源包含来自图层样式表单的填充不透明度属性信息。 |
| [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) | 类 KnkoResource。<br/>            此资源包含有关剪切元素混合的信息。 |
| [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/) | 图层节资源。 |
| [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) | 类 LclrResource。<br/>            此资源包含关于 PS 中图层列表中图层颜色的信息。仅此而已。 |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel/) | 用于在级别调整图层中处理通道的类 |
| [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) | 类 LevlResource。曝光调整图层的资源 |
| [Lfx2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lfx2resource/) | Lfx2 资源（效果资源） |
| [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) | 定义 PSD 文件中包含嵌入文件信息的 liFD 数据源类。<br/>            这是 PSD 文件格式操作 API 的一部分，用于帮助修改 Adobe® Photoshop® 文件。 |
| [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) | 定义 LnkeDataSource 类，该类包含有关外部链接文件的信息。<br/>            这是 PSD 文件格式操作 API 的一部分，可帮助修改 Adobe® Photoshop® 文件 |
| [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | 定义 LinkDataSource 类，该类包含有关 PSD 文件中链接文件或资产的信息。 |
| [LinkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/) | 定义 LinkResource 类，该类包含有关 PSD 格式图像中链接或嵌入文件的信息。<br/>            链接资源可能包含多个 [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) 实例，可在任何派生类中通过索引器访问。 |
| [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) | LMsk 资源。 |
| [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) | 定义包含 PSD 格式图像中嵌入文件信息的类。<br/>            链接资源可能包含多个 [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) 实例，可通过索引器访问。 |
| [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) | 定义包含 PSD 格式每通道 32 位图像中嵌入文件信息的类。<br/>            链接资源可能包含多个 [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) 实例，可通过索引器访问。 |
| [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) | 定义 LnkeResource 类，该类包含 PSD 格式图像中外部链接文件或资产的信息。<br/>            链接资源可能包含多个 [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 实例，可通过索引器访问。<br/>            这是 PSD 文件格式操作 API 的一部分，可帮助以编程方式修改 Adobe® Photoshop® 文件 |
| [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) | lnsrResource 类。 |
| [Lr16Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr16resource/) | lr16 资源。 |
| [Lr32Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr32resource/) | lr32 资源。 |
| [LrXxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lrxxresource/) | lrXX 资源。 |
| [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) | 图层受保护设置 |
| [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/) | 图层名称资源 |
| [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) | LyidResource 类。 |
| [LyvrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/) | 表示图层 Photoshop 版本的资源。 |
| [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) | MixrResource 类。通道混合器调整图层的资源 |
| [MlstResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/) | mlst 资源。<br/>            此类除其他功能外，还包含有关图层在时间轴上位置的信息。 |
| [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) | NvrtResource 类。反转调整图层的资源。 |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) | 表示 OS 类型结构。 |
| [OSTypeStructuresRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/) | 表示 [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 资源注册表。 |
| [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) | 贝塞尔曲线节点处的图形。 |
| [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) | PattResource 类。包含图案数据的资源 |
| [PattResourceData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/) | 用于存储 [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 资源的图案数据的类。 |
| [PhflResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/) | PhflResource 类。曝光调整图层的资源<br/>            2 版本 (= 3) 或 (= 2)<br/>            12 每个 XYZ 颜色 4 字节（仅在版本 3 中）<br/>            10 2 字节颜色空间，后跟 4 * 2 字节颜色分量（仅在版本 2 中）<br/>            4 密度<br/>            1 保持亮度 |
| [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) | PhflResource 类。曝光调整图层的资源<br/>            2 版本 (= 3) 或 (= 2)<br/>            12 每个 XYZ 颜色 4 字节（仅在版本 3 中）<br/>            10 2 字节颜色空间，后跟 4 * 2 字节颜色分量（仅在版本 2 中）<br/>            4 密度<br/>            1 保持亮度 |
| [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) | PhflResource 类。曝光调整图层的资源<br/>            2 版本 (= 3) 或 (= 2)<br/>            12 每个 XYZ 颜色 4 字节（仅在版本 3 中）<br/>            10 2 字节颜色空间，后跟 4 * 2 字节颜色分量（仅在版本 2 中）<br/>            4 密度<br/>            1 保持亮度 |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) | 定义 PlLdResource 类，该类包含 PSD 文件中放置图层的信息。<br/>            用于支持 Adobe® Photoshop® 图像中的智能对象图层。<br/>            在 Adobe® Photoshop® CS3 中已被 SoLdResource 替代 |
| [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/) | 定义 PlacedResource 类，该类包含 PSD 文件中已放置图层或智能对象图层的通用信息。<br/>            用于在 Adobe Photoshop 图像中支持智能对象图层。 |
| [PostResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/postresource/) | 类 PostResource。Posterize 图层设置。 |
| [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) | 类 PtFlResource。包含图案填充图层数据。 |
| [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) | 类 ShmdResource。元数据设置 |
| [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) | 定义 SmartObjectResource 类，该类包含 PSD 文件中智能对象图层的信息。<br/>            是 Sold 和 Sole 资源的基类，用于在 Adobe Photoshop 图像中支持智能对象图层。 |
| [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) | 定义 SmartResourceCreator 类，可创建 PlLd、SoLd 和 SoLe 资源。<br/>            用于在 Adobe Photoshop 图像中支持智能对象图层。 |
| [SoCoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/) | 类 SoCoResource。<br/>            此资源包含关于颜色填充图层的信息 |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) | 定义 SoLdResource 类，该类包含 PSD 文件中智能对象图层的信息。<br/>            用于在 Adobe Photoshop 图像中支持智能对象图层。 |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) | 定义 SoLeResource 类，该类包含 PSD 文件中智能对象图层的信息。<br/>            用于在 Adobe Photoshop 图像中支持带外部文件链接的智能对象图层。 |
| [Txt2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/) | Txt2 资源类 |
| [TypeToolFontInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo/) | 包含关于文字工具字体的信息。 |
| [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) | 文字工具信息。适用于 PSD 版本高于或等于 6.0 的情况。 |
| [TypeToolInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/) | 文字工具信息。适用于 PSD 版本低于 6.0 的情况。 |
| [TypeToolLineInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo/) | 文字工具行信息。 |
| [TypeToolStyleInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo/) | 文字工具样式信息。 |
| [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) | 未知资源。 |
| [VectorPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/) | 包含矢量路径的类。 |
| [VectorPathDataResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/) | 类 VectorPathDataResource。<br/>            此资源包含关于矢量图层蒙版的信息 |
| [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) | VibA 资源。 |
| [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) | 类 VmskResource。<br/>            此资源包含关于矢量图层蒙版的信息 |
| [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/) | 矢量起始数据资源。 |
| [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) | 类 VsmsResource。<br/>            此资源包含关于矢量图层蒙版的信息 |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | 图层锁定选项 |
| [LayerSectionSubtype](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionsubtype/) | 节子类型 |
| [LayerSectionType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectiontype/) | 图层节类型 |
| [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype/) | 定义 PSD 链接资源中数据源的 LinkDataSourceType 枚举。 |
| [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype/) | 发现可能的 Lnsr 资源类型。 |
| [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype/) | 定义已放置图层 PlLd 资源的 PlacedLayerType 枚举。 |
| [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | Sheet 颜色设置的可能颜色。<br/>            这是 PS 中图层列表的 UI 装饰颜色。 |
