---
title: "SmartObjectResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义 SmartObjectResource 类，包含 PSD 文件中智能对象图层的信息。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.ISmartObjectLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/ismartobjectlayerresource)
```
public abstract class SmartObjectResource extends PlacedResource implements ISmartObjectLayerResource
```

定义了 SmartObjectResource 类，该类包含有关 PSD 文件中智能对象图层的信息。它是 Sold 和 Sole 资源的基类，用于支持 Adobe Photoshop 图像中的智能对象图层。
## 字段

| 字段 | 描述 |
| --- | --- |
| [AntiAliasPolicyKey_internalized](#AntiAliasPolicyKey-internalized) | 抗锯齿策略键 |
| [BottomKey_internalized](#BottomKey-internalized) | 底部键 |
| [BoundsKey_internalized](#BoundsKey-internalized) | 边界键 |
| [CompIdKey_internalized](#CompIdKey-internalized) | CompID 的键名 |
| [CompInfoKey_internalized](#CompInfoKey-internalized) | comp 信息键名 |
| [CompKey_internalized](#CompKey-internalized) | comp 键 |
| [CompNoneValue_internalized](#CompNoneValue-internalized) | comp 值，表示 'none' |
| [CropKey_internalized](#CropKey-internalized) | 裁剪键 |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | 自定义信封变形名称 |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | 默认变形类名称 |
| [DenominatorKey_internalized](#DenominatorKey-internalized) | 分母键 |
| [DurationKey_internalized](#DurationKey-internalized) | 持续时间键 |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | 默认变形类名称 |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | 预期的变形描述符版本 |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | 预期的变形版本 |
| [FrameCountKey_internalized](#FrameCountKey-internalized) | 帧计数键 |
| [FrameStepKey_internalized](#FrameStepKey-internalized) | 帧步长键 |
| [HeightKey_internalized](#HeightKey-internalized) | 高度键 |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | 水平标识符名称 |
| [IdentKey_internalized](#IdentKey-internalized) | 唯一标识符键 |
| [ItemsPropertyCannotBeNull_internalized](#ItemsPropertyCannotBeNull-internalized) | items 属性不能为空 |
| [LeftKey_internalized](#LeftKey-internalized) | 左键 |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | 网格点键名称 |
| [NonAffineTransformKey_internalized](#NonAffineTransformKey-internalized) | 非仿射变换键 |
| [NullClassId_internalized](#NullClassId-internalized) | 空类标识符 |
| [NumeratorKey_internalized](#NumeratorKey-internalized) | 分子键 |
| [OptionalKeys_internalized](#OptionalKeys-internalized) | 可选键的集合 |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | 方向标识符名称 |
| [OriginalCompIdKey_internalized](#OriginalCompIdKey-internalized) | 原始 CompID 的键名 |
| [PageNumberKey_internalized](#PageNumberKey-internalized) | 页码键 |
| [PlacedIdKey_internalized](#PlacedIdKey-internalized) | 已放置标识符键 |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | 预期的版本值 |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB header version。 |
| [PsbResourceSignature](#PsbResourceSignature) | PSB-specific resource signature。 |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD header version。 |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | 有理点类标识符名称 |
| [ResolutionKey_internalized](#ResolutionKey-internalized) | 分辨率键 |
| [ResourceSignature](#ResourceSignature) | common resource signature。 |
| [RightKey_internalized](#RightKey-internalized) | 右键 |
| [SizeKey_internalized](#SizeKey-internalized) | 大小键 |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | double 的大小 |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | int 的大小 |
| [SmartVersionValue_internalized](#SmartVersionValue-internalized) | 预期的智能对象资源版本值。 |
| [TopKey_internalized](#TopKey-internalized) | 顶部键 |
| [TotalPagesKey_internalized](#TotalPagesKey-internalized) | 总页数键 |
| [TransformKey_internalized](#TransformKey-internalized) | 变换键 |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | 变换值的计数 |
| [TypeKey_internalized](#TypeKey-internalized) | 类型键 |
| [TypeValue_internalized](#TypeValue-internalized) | 预期的类型值。 |
| [UOrderKey_internalized](#UOrderKey-internalized) | u 顺序键 |
| [VOrderKey_internalized](#VOrderKey-internalized) | v 顺序键 |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | 垂直标识符名称 |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | 扭曲自定义名称 |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | 扭曲标题长度。 |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | 扭曲标题长度。 |
| [WarpKey_internalized](#WarpKey-internalized) | 扭曲键。 |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | 扭曲无名称 |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | 扭曲透视键 |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | 扭曲透视其他 |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | 扭曲旋转键 |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | 扭曲样式键 |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | 扭曲值键 |
| [WidthKey_internalized](#WidthKey-internalized) | 宽度键 |
| [YouCannotAccessCropPropertyMessage_internalized](#YouCannotAccessCropPropertyMessage-internalized) | 无法访问 Crop 属性的消息 |
| [YouCannotSetCompIdPropertyMessage_internalized](#YouCannotSetCompIdPropertyMessage-internalized) | 无法设置 CompId 属性的消息 |
| [YouCannotSetCompPropertyMessage_internalized](#YouCannotSetCompPropertyMessage-internalized) | 无法设置 Comp 属性的消息 |
| [YouCannotSetOriginalCompIdPropertyMessage_internalized](#YouCannotSetOriginalCompIdPropertyMessage-internalized) | 无法设置 OriginalCompId 属性的消息 |
| [ZeroChar_internalized](#ZeroChar-internalized) | 零字符。 |
| [ventureLicense_internalized](#ventureLicense-internalized) | venture license。 |
## Methods

| Method | 描述 |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | 断言指定的实际值等于预期值。 |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 检查并设置资源是否为 PSB specific。 |
| [convertListStructureToDoubleArray_internalized(ListStructure list)](#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-) | 将列表结构转换为双精度数组。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | 获取或设置 PSD 图像中智能对象图层数据的抗锯齿策略。 |
| [getBottom()](#getBottom--) | 获取或设置 PSD 图像中已放置图层的底部位置。 |
| [getBounds()](#getBounds--) | 获取或设置 PSD 文件中已放置图层的边界。 |
| [getClass()](#getClass--) |  |
| [getComp()](#getComp--) | 获取或设置 PSD 文件中智能对象图层数据的 comp 值。 |
| [getCompId()](#getCompId--) | 获取或设置子文档当前选定的 comp 的 ID，如果未选中则为 -1。 |
| [getCrop()](#getCrop--) | 获取或设置 PSD 图像中智能对象图层数据的 crop。 |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | 获取或设置分配值（如 Left、Top、Right、Bottom、TransformMatrix）的默认单位类型。 |
| [getDurationDenominator()](#getDurationDenominator--) | 获取或设置持续时间的分母。 |
| [getDurationNumerator()](#getDurationNumerator--) | 获取或设置持续时间的分子。 |
| [getFrameCount()](#getFrameCount--) | 获取或设置 PSD 文件中智能对象图层数据的帧计数。 |
| [getFrameStepDenominator()](#getFrameStepDenominator--) | 获取或设置帧步长的分母。 |
| [getFrameStepNumerator()](#getFrameStepNumerator--) | 获取或设置帧步长的分子。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getHeight()](#getHeight--) | 获取或设置高度。 |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | 获取或设置水平网格点的测量单位。 |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| [getItems()](#getItems--) | 获取或设置 PSD 文件中智能对象图层数据的描述符项。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLeft()](#getLeft--) | 获取或设置 PSD 文件中已放置图层的左侧位置。 |
| [getLength()](#getLength--) | 获取智能对象资源的字节长度。 |
| [getNonAffineTransformMatrix()](#getNonAffineTransformMatrix--) | 获取或设置 PSD 文件中智能对象图层数据的非仿射变换矩阵。 |
| [getOriginalCompId()](#getOriginalCompId--) | 获取当前为子文档选择的 Comp 的原始 ID，如果未选择则为 -1。 |
| [getPageNumber()](#getPageNumber--) | 获取或设置 PSD 文件中智能对象图层数据的页码。 |
| [getPerspective()](#getPerspective--) | 获取或设置放置在 PSD 文件中的图层的透视值。 |
| [getPerspectiveOther()](#getPerspectiveOther--) | 获取或设置放置在 PSD 文件中的图层的其他透视值。 |
| [getPlacedId()](#getPlacedId--) | 获取或设置此 PSD 图像中智能对象图层数据的唯一标识符。 |
| [getPlacedId_internalized()](#getPlacedId-internalized--) |  |
| [getPlacedLayerType()](#getPlacedLayerType--) | 获取或设置 PSD 文件中智能对象图层数据的类型。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getResolution()](#getResolution--) | 获取或设置 PSD 文件中智能对象图层数据的分辨率。 |
| [getResolutionUnit()](#getResolutionUnit--) | 获取或设置 PSD 文件中智能对象图层数据的分辨率测量单位。 |
| [getRight()](#getRight--) | 获取或设置放置在 PSD 文件中的图层的右侧位置。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [getTop()](#getTop--) | 获取或设置放置在 PSD 图像中的图层的顶部位置。 |
| [getTotalPages()](#getTotalPages--) | 获取或设置 PSD 文件中智能对象图层数据的总页数。 |
| [getTransformMatrix()](#getTransformMatrix--) | 获取或设置 PSD 文件中智能对象图层数据的变换矩阵。 |
| [getUOrder()](#getUOrder--) | 获取或设置放置在 PSD 文件中的图层的 U 顺序值。 |
| [getUniqueId()](#getUniqueId--) | 获取或设置 PSD 图像中智能对象图层数据的全局唯一标识符 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)。 |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | 获取或设置放置在 PSD 文件中的图层的 V 顺序值。 |
| [getValue()](#getValue--) | 获取或设置放置在 PSD 图像中的图层的扭曲值。 |
| [getVersion()](#getVersion--) | 获取放置在 PSD 文件中的图层的版本，通常为 3。 |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | 获取或设置垂直网格点的度量单位。 |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | 获取或设置类 ID。 |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | 获取或设置扭曲类名。 |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | 获取或设置扭曲描述符版本。 |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | 变形项。 |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | 获取或设置扭曲版本。 |
| [getWidth()](#getWidth--) | 获取或设置宽度。 |
| [get_Item(String index)](#get-Item-java.lang.String-) | 获取在指定索引处的 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)。 |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | 获取一个值，指示此实例是否具有边界单位。 |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeBounds_internalized(Rectangle bounds)](#initializeBounds-internalized-com.aspose.psd.Rectangle-) | 初始化边界和矩阵。 |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | 获取或设置一个值，指示此实例的扭曲样式是否为自定义。 |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | 获取或设置一个值，指示此实例的旋转方向是否为水平。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将智能对象资源保存到指定的流容器中。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | 获取或设置 PSD 图像中智能对象图层数据的抗锯齿策略。 |
| [setBottom(double value)](#setBottom-double-) | 获取或设置 PSD 图像中已放置图层的底部位置。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | 获取或设置 PSD 文件中已放置图层的边界。 |
| [setComp(int value)](#setComp-int-) | 获取或设置 PSD 文件中智能对象图层数据的 comp 值。 |
| [setCompId(int value)](#setCompId-int-) | 获取或设置子文档当前选定的 comp 的 ID，如果未选中则为 -1。 |
| [setCrop(int value)](#setCrop-int-) | 获取或设置 PSD 图像中智能对象图层数据的 crop。 |
| [setCustom(boolean value)](#setCustom-boolean-) | 获取或设置一个值，指示此实例的扭曲样式是否为自定义。 |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | 获取或设置分配值（如 Left、Top、Right、Bottom、TransformMatrix）的默认单位类型。 |
| [setDurationDenominator(int value)](#setDurationDenominator-int-) | 获取或设置持续时间的分母。 |
| [setDurationNumerator(int value)](#setDurationNumerator-int-) | 获取或设置持续时间的分子。 |
| [setFrameCount(int value)](#setFrameCount-int-) | 获取或设置 PSD 文件中智能对象图层数据的帧计数。 |
| [setFrameStepDenominator(int value)](#setFrameStepDenominator-int-) | 获取或设置帧步长的分母。 |
| [setFrameStepNumerator(int value)](#setFrameStepNumerator-int-) | 获取或设置帧步长的分子。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setHeight(double value)](#setHeight-double-) | 获取或设置高度。 |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | 获取或设置水平网格点的测量单位。 |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 获取或设置 PSD 文件中智能对象图层数据的描述符项。 |
| [setLeft(double value)](#setLeft-double-) | 获取或设置 PSD 文件中已放置图层的左侧位置。 |
| [setNonAffineTransformMatrix(double[] value)](#setNonAffineTransformMatrix-double---) | 获取或设置 PSD 文件中智能对象图层数据的非仿射变换矩阵。 |
| [setOriginalCompId_internalized(int value)](#setOriginalCompId-internalized-int-) | 获取当前为子文档选择的 Comp 的原始 ID，如果未选择则为 -1。 |
| [setPageNumber(int value)](#setPageNumber-int-) | 获取或设置 PSD 文件中智能对象图层数据的页码。 |
| [setPerspective(double value)](#setPerspective-double-) | 获取或设置放置在 PSD 文件中的图层的透视值。 |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | 获取或设置放置在 PSD 文件中的图层的其他透视值。 |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | 获取或设置此 PSD 图像中智能对象图层数据的唯一标识符。 |
| [setPlacedId_internalized(System.Guid value)](#setPlacedId-internalized-com.aspose.ms.System.Guid-) |  |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | 获取或设置 PSD 文件中智能对象图层数据的类型。 |
| [setResolution(double value)](#setResolution-double-) | 获取或设置 PSD 文件中智能对象图层数据的分辨率。 |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | 获取或设置 PSD 文件中智能对象图层数据的分辨率测量单位。 |
| [setRight(double value)](#setRight-double-) | 获取或设置放置在 PSD 文件中的图层的右侧位置。 |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | 获取或设置一个值，指示此实例的旋转方向是否为水平。 |
| [setTop(double value)](#setTop-double-) | 获取或设置放置在 PSD 图像中的图层的顶部位置。 |
| [setTotalPages(int value)](#setTotalPages-int-) | 获取或设置 PSD 文件中智能对象图层数据的总页数。 |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | 获取或设置 PSD 文件中智能对象图层数据的变换矩阵。 |
| [setUOrder(int value)](#setUOrder-int-) | 获取或设置放置在 PSD 文件中的图层的 U 顺序值。 |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | 获取或设置 PSD 图像中智能对象图层数据的全局唯一标识符 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)。 |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | 获取或设置放置在 PSD 文件中的图层的 V 顺序值。 |
| [setValue(double value)](#setValue-double-) | 获取或设置放置在 PSD 图像中的图层的扭曲值。 |
| [setVersion(int value)](#setVersion-int-) | 获取放置在 PSD 文件中的图层的版本，通常为 3。 |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | 获取或设置垂直网格点的度量单位。 |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | 获取或设置类 ID。 |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | 获取或设置扭曲类名。 |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | 获取或设置扭曲描述符版本。 |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | 获取或设置扭曲版本。 |
| [setWidth(double value)](#setWidth-double-) | 获取或设置宽度。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AntiAliasPolicyKey_internalized {#AntiAliasPolicyKey-internalized}
```
public static final String AntiAliasPolicyKey_internalized
```


抗锯齿策略键

### BottomKey_internalized {#BottomKey-internalized}
```
public static final String BottomKey_internalized
```


底部键

### BoundsKey_internalized {#BoundsKey-internalized}
```
public static final String BoundsKey_internalized
```


边界键

### CompIdKey_internalized {#CompIdKey-internalized}
```
public static final String CompIdKey_internalized
```


CompID 的键名

### CompInfoKey_internalized {#CompInfoKey-internalized}
```
public static final String CompInfoKey_internalized
```


comp 信息键名

### CompKey_internalized {#CompKey-internalized}
```
public static final String CompKey_internalized
```


comp 键

### CompNoneValue_internalized {#CompNoneValue-internalized}
```
public static final int CompNoneValue_internalized
```


comp 值，表示 'none'

### CropKey_internalized {#CropKey-internalized}
```
public static final String CropKey_internalized
```


裁剪键

### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


自定义信封变形名称

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


默认变形类名称

### DenominatorKey_internalized {#DenominatorKey-internalized}
```
public static final String DenominatorKey_internalized
```


分母键

### DurationKey_internalized {#DurationKey-internalized}
```
public static final String DurationKey_internalized
```


持续时间键

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


默认变形类名称

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


预期的变形描述符版本

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


预期的变形版本

### FrameCountKey_internalized {#FrameCountKey-internalized}
```
public static final String FrameCountKey_internalized
```


帧计数键

### FrameStepKey_internalized {#FrameStepKey-internalized}
```
public static final String FrameStepKey_internalized
```


帧步长键

### HeightKey_internalized {#HeightKey-internalized}
```
public static final String HeightKey_internalized
```


高度键

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


水平标识符名称

### IdentKey_internalized {#IdentKey-internalized}
```
public static final String IdentKey_internalized
```


唯一标识符键

### ItemsPropertyCannotBeNull_internalized {#ItemsPropertyCannotBeNull-internalized}
```
public static final String ItemsPropertyCannotBeNull_internalized
```


items 属性不能为空

### LeftKey_internalized {#LeftKey-internalized}
```
public static final String LeftKey_internalized
```


左键

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


网格点键名称

### NonAffineTransformKey_internalized {#NonAffineTransformKey-internalized}
```
public static final String NonAffineTransformKey_internalized
```


非仿射变换键

### NullClassId_internalized {#NullClassId-internalized}
```
public static final String NullClassId_internalized
```


空类标识符

### NumeratorKey_internalized {#NumeratorKey-internalized}
```
public static final String NumeratorKey_internalized
```


分子键

### OptionalKeys_internalized {#OptionalKeys-internalized}
```
public static final String[] OptionalKeys_internalized
```


可选键的集合

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


方向标识符名称

### OriginalCompIdKey_internalized {#OriginalCompIdKey-internalized}
```
public static final String OriginalCompIdKey_internalized
```


原始 CompID 的键名

### PageNumberKey_internalized {#PageNumberKey-internalized}
```
public static final String PageNumberKey_internalized
```


页码键

### PlacedIdKey_internalized {#PlacedIdKey-internalized}
```
public static final String PlacedIdKey_internalized
```


已放置标识符键

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


预期的版本值

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB header version。

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB-specific resource signature。

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD header version。

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


有理点类标识符名称

### ResolutionKey_internalized {#ResolutionKey-internalized}
```
public static final String ResolutionKey_internalized
```


分辨率键

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


common resource signature。

### RightKey_internalized {#RightKey-internalized}
```
public static final String RightKey_internalized
```


右键

### SizeKey_internalized {#SizeKey-internalized}
```
public static final String SizeKey_internalized
```


大小键

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


double 的大小

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


int 的大小

### SmartVersionValue_internalized {#SmartVersionValue-internalized}
```
public static final int SmartVersionValue_internalized
```


预期的智能对象资源版本值。

### TopKey_internalized {#TopKey-internalized}
```
public static final String TopKey_internalized
```


顶部键

### TotalPagesKey_internalized {#TotalPagesKey-internalized}
```
public static final String TotalPagesKey_internalized
```


总页数键

### TransformKey_internalized {#TransformKey-internalized}
```
public static final String TransformKey_internalized
```


变换键

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


变换值的计数

### TypeKey_internalized {#TypeKey-internalized}
```
public static final String TypeKey_internalized
```


类型键

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


预期的类型值。

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


u 顺序键

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


v 顺序键

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


垂直标识符名称

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


扭曲自定义名称

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


扭曲标题长度。

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


扭曲标题长度。

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


warp 键。也是默认的 warp 类名。

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


扭曲无名称

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


扭曲透视键

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


扭曲透视其他

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


扭曲旋转键

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


扭曲样式键

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


扭曲值键

### WidthKey_internalized {#WidthKey-internalized}
```
public static final String WidthKey_internalized
```


宽度键

### YouCannotAccessCropPropertyMessage_internalized {#YouCannotAccessCropPropertyMessage-internalized}
```
public static final String YouCannotAccessCropPropertyMessage_internalized
```


无法访问 Crop 属性的消息

### YouCannotSetCompIdPropertyMessage_internalized {#YouCannotSetCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetCompIdPropertyMessage_internalized
```


无法设置 CompId 属性的消息

### YouCannotSetCompPropertyMessage_internalized {#YouCannotSetCompPropertyMessage-internalized}
```
public static final String YouCannotSetCompPropertyMessage_internalized
```


无法设置 Comp 属性的消息

### YouCannotSetOriginalCompIdPropertyMessage_internalized {#YouCannotSetOriginalCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetOriginalCompIdPropertyMessage_internalized
```


无法设置 OriginalCompId 属性的消息

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


零字符。

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


venture license。

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


断言指定的实际值等于预期值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| actualValue | java.lang.Object | 实际值。 |
| expectedValue | java.lang.Object | 预期值。 |
| message | java.lang.String | 消息。 |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


检查并设置资源是否为 PSB 特定。某些资源目前尚未被识别，但我们拥有完整的 PSB 特定资源列表，这会在保存时改变它们的行为。因此至少需要在 UnknownResource 中进行此检查。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | int | 键。 |

### convertListStructureToDoubleArray_internalized(ListStructure list) {#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-}
```
public static double[] convertListStructureToDoubleArray_internalized(ListStructure list)
```


将列表结构转换为双精度数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| list | [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) | ListStructure 实例。 |

**Returns:**
double[] - 创建的 double[] 数组。
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


获取或设置 PSD 图像中智能对象图层数据的抗锯齿策略。

值：智能对象图层数据的抗锯齿策略。

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


获取或设置 PSD 图像中已放置图层的底部位置。

值：已放置图层的底部位置。

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


获取或设置 PSD 文件中已放置图层的边界。

值：已放置图层的边界。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComp() {#getComp--}
```
public final int getComp()
```


获取或设置 PSD 文件中智能对象图层数据的 comp 值。智能对象中的图层组合

值：comp 值，如果没有则为 -1。

**Returns:**
int
### getCompId() {#getCompId--}
```
public final int getCompId()
```


获取或设置子文档当前选定的 comp 的 ID，如果未选中则为 -1。Comp 是设计师可以创建的页面布局的组合。使用图层组合，您可以在单个 Adobe\ufffd Photoshop\ufffd 文件中创建、管理和查看布局的多个版本。图层组合是图层面板状态的快照。图层组合保存三种图层选项，但此属性获取 PSD 文件中智能对象图层的图层组合选择标识符。智能对象中的图层组合

值：PSD 图像中子文档当前选定的 comp 的 ID，如果未选中则为 -1。

**Returns:**
int
### getCrop() {#getCrop--}
```
public final int getCrop()
```


获取或设置 PSD 图像中智能对象图层数据的 crop。

值：已放置图层信息的裁剪值。

**Returns:**
int
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


获取或设置分配值（如 Left、Top、Right、Bottom、TransformMatrix）的默认单位类型。

值：默认测量单位类型。

**Returns:**
int
### getDurationDenominator() {#getDurationDenominator--}
```
public final int getDurationDenominator()
```


获取或设置持续时间的分母。

值：持续时间的分母。

**Returns:**
int
### getDurationNumerator() {#getDurationNumerator--}
```
public final int getDurationNumerator()
```


获取或设置持续时间的分子。

值：持续时间的分子。

**Returns:**
int
### getFrameCount() {#getFrameCount--}
```
public final int getFrameCount()
```


获取或设置 PSD 文件中智能对象图层数据的帧计数。

值：已放置图层信息的帧计数。

**Returns:**
int
### getFrameStepDenominator() {#getFrameStepDenominator--}
```
public final int getFrameStepDenominator()
```


获取或设置帧步长的分母。

值：帧步长的分母。

**Returns:**
int
### getFrameStepNumerator() {#getFrameStepNumerator--}
```
public final int getFrameStepNumerator()
```


获取或设置帧步长的分子。

值：帧步长的分子。

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


获取或设置标题。

值：头部。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取或设置高度。

Value: 高度。

**Returns:**
double
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


获取或设置水平网格点的测量单位。

值：水平网格点的测量单位。

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


获取或设置 PSD 文件中已放置图层的水平网格点。

值：已放置图层的水平网格点。

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


获取或设置 PSD 文件中智能对象图层数据的描述符项。

值：已放置图层信息的描述符项。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


获取图层资源键。

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


获取或设置 PSD 文件中已放置图层的左侧位置。

值：已放置图层的左侧位置。

**Returns:**
double
### getLength() {#getLength--}
```
public int getLength()
```


获取智能对象资源的字节长度。

**Returns:**
int
### getNonAffineTransformMatrix() {#getNonAffineTransformMatrix--}
```
public final double[] getNonAffineTransformMatrix()
```


获取或设置 PSD 文件中智能对象图层数据的非仿射变换矩阵。

值：智能对象图层的非仿射变换矩阵。

**Returns:**
double[]
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


获取当前为子文档选中的 Comp 的原始 ID，如果未选中则为 -1。此属性获取 PSD 文件中智能对象图层的原始图层 Comp 选择标识符。智能对象中的图层组合。

值：PSD 图像中子文档当前选中的 comp 的原始 ID，如果未选中则为 -1。

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


获取或设置 PSD 文件中智能对象图层数据的页码。

值：智能对象图层数据的页码。

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


获取或设置放置在 PSD 文件中的图层的透视值。

值：已放置图层的透视值。

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


获取或设置放置在 PSD 文件中的图层的其他透视值。

值：已放置图层的其他透视值。

**Returns:**
double
### getPlacedId() {#getPlacedId--}
```
public final UUID getPlacedId()
```


获取或设置此 PSD 图像中智能对象图层数据的唯一标识符。

值：此智能对象图层资源的唯一标识符。

**Returns:**
java.util.UUID
### getPlacedId_internalized() {#getPlacedId-internalized--}
```
public final System.Guid getPlacedId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


获取或设置 PSD 文件中智能对象图层数据的类型。

值：智能对象图层数据的类型。

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


获取前缀长度。默认值为 8BIM 资源的 12，8B64 资源的 16。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| psdVersion | int | PSD 版本。 |

**Returns:**
int - 前缀长度。
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


获取图层资源所需的最低 PSD 版本。0 表示没有限制。

**Returns:**
int
### getResolution() {#getResolution--}
```
public final double getResolution()
```


获取或设置 PSD 文件中智能对象图层数据的分辨率。

值：智能对象图层的分辨率。

**Returns:**
double
### getResolutionUnit() {#getResolutionUnit--}
```
public final int getResolutionUnit()
```


获取或设置 PSD 文件中智能对象图层数据的分辨率测量单位。

值：智能对象图层的分辨率测量单位。

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


获取或设置放置在 PSD 文件中的图层的右侧位置。

值：已放置图层的右侧位置。

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


获取图层资源签名。

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


获取或设置放置在 PSD 图像中的图层的顶部位置。

值：已放置图层的顶部位置。

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


获取或设置 PSD 文件中智能对象图层数据的总页数。

值：智能对象图层数据的总页数。

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


获取或设置 PSD 文件中智能对象图层数据的变换矩阵。

值：智能对象图层数据的变换矩阵。

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


获取或设置放置在 PSD 文件中的图层的 U 顺序值。

值：已放置图层的U顺序值。

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


获取或设置 PSD 图像中智能对象图层数据的全局唯一标识符 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)。

值：智能对象图层数据的全局唯一标识符 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)。

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public final int getVOrder()
```


获取或设置放置在 PSD 文件中的图层的 V 顺序值。

值：已放置图层的V顺序值。

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


获取或设置放置在 PSD 图像中的图层的扭曲值。

值：已放置图层的扭曲值。

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


获取放置在 PSD 文件中的图层的版本，通常为 3。

值：已放置图层的版本。

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


获取或设置垂直网格点的度量单位。

值：垂直网格点的测量单位。

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


获取或设置 PSD 文件中已放置图层的水平网格点。

值：已放置图层的水平网格点。

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


获取或设置类 ID。

值：类标识符。

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


获取或设置扭曲类名。

值：扭曲类名。

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


获取或设置扭曲描述符版本。

值： 扭曲描述符版本。

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


变形项。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


获取或设置扭曲版本。

值： 扭曲版本。

**Returns:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取或设置宽度。

Value: 宽度。

**Returns:**
double
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


获取在指定索引处的 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| index | java.lang.String | 键名。 |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


获取一个值，指示此实例是否具有边界单位。

值：  true  如果此实例具有边界单位；否则，  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initProreties_internalized(PlaceResourceParams plLdResourceParams) {#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public final void initProreties_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### initializeBounds_internalized(Rectangle bounds) {#initializeBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void initializeBounds_internalized(Rectangle bounds)
```


初始化边界和矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 边界。 |

### initializeItems_internalized() {#initializeItems-internalized--}
```
public void initializeItems_internalized()
```




### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


获取或设置一个值，指示此实例的扭曲样式是否为自定义。如果为 true，则包含网格点。如果设置为 false，则擦除网格点。

值：  true  如果放置的图层具有自定义样式；否则，  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


确定资源是否为 PSB specific。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | int | 资源键。 |

**Returns:**
boolean - 如果资源是 PSB 特定则为 true；否则为 false。
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


获取指示此实例是否为资源 PSB specific 的值。

值：如果此实例是资源 PSD 特定则为 true；否则为 false。

**Returns:**
boolean
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


获取或设置一个值，指示此实例的旋转方向是否为水平。

值：  true  如果旋转方向为水平；否则，  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


将智能对象资源保存到指定的流容器中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psdVersion | int | PSD 版本。 |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


保存自定义资源头部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |
| 签名 | int | 签名。 |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


保存头部签名、标识符和长度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |
| 签名 | int | 签名。 |
| isLengthLong | boolean | 如果设置为 true，则长度为长。 |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


获取或设置 PSD 图像中智能对象图层数据的抗锯齿策略。

值：智能对象图层数据的抗锯齿策略。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


获取或设置 PSD 图像中已放置图层的底部位置。

值：已放置图层的底部位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


获取或设置 PSD 文件中已放置图层的边界。

值：已放置图层的边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setComp(int value) {#setComp-int-}
```
public final void setComp(int value)
```


获取或设置 PSD 文件中智能对象图层数据的 comp 值。智能对象中的图层组合

值：comp 值，如果没有则为 -1。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


获取或设置子文档当前选定的 comp 的 ID，如果未选中则为 -1。Comp 是设计师可以创建的页面布局的组合。使用图层组合，您可以在单个 Adobe\ufffd Photoshop\ufffd 文件中创建、管理和查看布局的多个版本。图层组合是图层面板状态的快照。图层组合保存三种图层选项，但此属性获取 PSD 文件中智能对象图层的图层组合选择标识符。智能对象中的图层组合

值：PSD 图像中子文档当前选定的 comp 的 ID，如果未选中则为 -1。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setCrop(int value) {#setCrop-int-}
```
public final void setCrop(int value)
```


获取或设置 PSD 图像中智能对象图层数据的 crop。

值：已放置图层信息的裁剪值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


获取或设置一个值，指示此实例的扭曲样式是否为自定义。如果为 true，则包含网格点。如果设置为 false，则擦除网格点。

值：  true  如果放置的图层具有自定义样式；否则，  false .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


获取或设置分配值（如 Left、Top、Right、Bottom、TransformMatrix）的默认单位类型。

值：默认测量单位类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setDurationDenominator(int value) {#setDurationDenominator-int-}
```
public final void setDurationDenominator(int value)
```


获取或设置持续时间的分母。

值：持续时间的分母。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setDurationNumerator(int value) {#setDurationNumerator-int-}
```
public final void setDurationNumerator(int value)
```


获取或设置持续时间的分子。

值：持续时间的分子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFrameCount(int value) {#setFrameCount-int-}
```
public final void setFrameCount(int value)
```


获取或设置 PSD 文件中智能对象图层数据的帧计数。

值：已放置图层信息的帧计数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFrameStepDenominator(int value) {#setFrameStepDenominator-int-}
```
public final void setFrameStepDenominator(int value)
```


获取或设置帧步长的分母。

值：帧步长的分母。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFrameStepNumerator(int value) {#setFrameStepNumerator-int-}
```
public final void setFrameStepNumerator(int value)
```


获取或设置帧步长的分子。

值：帧步长的分子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


获取或设置标题。

值：头部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


获取或设置高度。

Value: 高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


获取或设置水平网格点的测量单位。

值：水平网格点的测量单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


获取或设置 PSD 文件中已放置图层的水平网格点。

值：已放置图层的水平网格点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


获取或设置 PSD 文件中智能对象图层数据的描述符项。

值：已放置图层信息的描述符项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


获取或设置 PSD 文件中已放置图层的左侧位置。

值：已放置图层的左侧位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setNonAffineTransformMatrix(double[] value) {#setNonAffineTransformMatrix-double---}
```
public final void setNonAffineTransformMatrix(double[] value)
```


获取或设置 PSD 文件中智能对象图层数据的非仿射变换矩阵。

值：智能对象图层的非仿射变换矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setOriginalCompId_internalized(int value) {#setOriginalCompId-internalized-int-}
```
public final void setOriginalCompId_internalized(int value)
```


获取当前为子文档选中的 Comp 的原始 ID，如果未选中则为 -1。此属性获取 PSD 文件中智能对象图层的原始图层 Comp 选择标识符。智能对象中的图层组合。

值：PSD 图像中子文档当前选中的 comp 的原始 ID，如果未选中则为 -1。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


获取或设置 PSD 文件中智能对象图层数据的页码。

值：智能对象图层数据的页码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


获取或设置放置在 PSD 文件中的图层的透视值。

值：已放置图层的透视值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


获取或设置放置在 PSD 文件中的图层的其他透视值。

值：已放置图层的其他透视值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public final void setPlacedId(UUID value)
```


获取或设置此 PSD 图像中智能对象图层数据的唯一标识符。

值：此智能对象图层资源的唯一标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID |  |

### setPlacedId_internalized(System.Guid value) {#setPlacedId-internalized-com.aspose.ms.System.Guid-}
```
public final void setPlacedId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.Guid |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


获取或设置 PSD 文件中智能对象图层数据的类型。

值：智能对象图层数据的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setResolution(double value) {#setResolution-double-}
```
public final void setResolution(double value)
```


获取或设置 PSD 文件中智能对象图层数据的分辨率。

值：智能对象图层的分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public final void setResolutionUnit(int value)
```


获取或设置 PSD 文件中智能对象图层数据的分辨率测量单位。

值：智能对象图层的分辨率测量单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


获取或设置放置在 PSD 文件中的图层的右侧位置。

值：已放置图层的右侧位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


获取或设置一个值，指示此实例的旋转方向是否为水平。

值：  true  如果旋转方向为水平；否则，  false .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


获取或设置放置在 PSD 图像中的图层的顶部位置。

值：已放置图层的顶部位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


获取或设置 PSD 文件中智能对象图层数据的总页数。

值：智能对象图层数据的总页数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


获取或设置 PSD 文件中智能对象图层数据的变换矩阵。

值：智能对象图层数据的变换矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


获取或设置放置在 PSD 文件中的图层的 U 顺序值。

值：已放置图层的U顺序值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


获取或设置 PSD 图像中智能对象图层数据的全局唯一标识符 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)。

值：智能对象图层数据的全局唯一标识符 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


获取或设置放置在 PSD 文件中的图层的 V 顺序值。

值：已放置图层的V顺序值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


获取或设置放置在 PSD 图像中的图层的扭曲值。

值：已放置图层的扭曲值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


获取放置在 PSD 文件中的图层的版本，通常为 3。

值：已放置图层的版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


获取或设置垂直网格点的度量单位。

值：垂直网格点的测量单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


获取或设置 PSD 文件中已放置图层的水平网格点。

值：已放置图层的水平网格点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


获取或设置类 ID。

值：类标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


获取或设置扭曲类名。

值：扭曲类名。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


获取或设置扭曲描述符版本。

值： 扭曲描述符版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


获取或设置扭曲版本。

值： 扭曲版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


获取或设置宽度。

Value: 宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的字符串。

**Returns:**
java.lang.String - 表示此实例的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

