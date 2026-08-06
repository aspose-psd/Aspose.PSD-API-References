---
title: "PlLdResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义 PlLdResource 类，包含 PSD 文件中已放置图层的信息。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource)
```
public class PlLdResource extends PlacedResource
```

定义 PlLdResource 类，该类包含 PSD 文件中已放置图层的信息。它用于在 Adobe® Photoshop® 图像中支持智能对象图层。它在 Adobe® Photoshop® CS3 中被 SoLdResource 替代。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PlLdResource()](#PlLdResource--) | 初始化 [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | 自定义信封变形名称 |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | 默认变形类名称 |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | 默认变形类名称 |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | 预期的变形描述符版本 |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | 预期的变形版本 |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | 水平标识符名称 |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | 网格点键名称 |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | 方向标识符名称 |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | 预期的版本值 |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB header version。 |
| [PsbResourceSignature](#PsbResourceSignature) | PSB-specific resource signature。 |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD header version。 |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | 有理点类标识符名称 |
| [ResourceSignature](#ResourceSignature) | common resource signature。 |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | double 的大小 |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | int 的大小 |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | 变换值的计数 |
| [TypeToolKey](#TypeToolKey) | 类型工具信息键。 |
| [TypeValue_internalized](#TypeValue-internalized) | 预期的类型值 |
| [UOrderKey_internalized](#UOrderKey-internalized) | u 顺序键 |
| [VOrderKey_internalized](#VOrderKey-internalized) | v 顺序键 |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | 垂直标识符名称 |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | 扭曲自定义名称 |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | 扭曲标题长度。 |
| [WarpKey_internalized](#WarpKey-internalized) | 扭曲键。 |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | 扭曲无名称 |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | 扭曲透视键 |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | 扭曲透视其他 |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | 扭曲旋转键 |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | 扭曲样式键 |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | 扭曲值键 |
| [ZeroChar_internalized](#ZeroChar-internalized) | 零字符。 |
| [ventureLicense_internalized](#ventureLicense-internalized) | venture license。 |
## Methods

| Method | 描述 |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | 断言指定的实际值等于预期值。 |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 检查并设置资源是否为 PSB specific。 |
| [create_internalized(PlaceResourceParams plLdResourceParams)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [create_internalized(System.Guid uniqueId, boolean isCustom)](#create-internalized-com.aspose.ms.System.Guid-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | 获取或设置 PSD 图像中已放置图层的抗锯齿策略。 |
| [getBottom()](#getBottom--) | 获取或设置 PSD 图像中已放置图层的底部位置。 |
| [getBounds()](#getBounds--) | 获取或设置 PSD 文件中已放置图层的边界。 |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | 获取或设置分配值（如 Left、Top、Right、Bottom、TransformMatrix）的默认单位类型。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | 获取或设置水平网格点的测量单位。 |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| [getItems()](#getItems--) | 获取或设置扭曲项。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLeft()](#getLeft--) | 获取或设置 PSD 文件中已放置图层的左侧位置。 |
| [getLength()](#getLength--) | 获取 PlLd 资源的字节长度。 |
| [getPageNumber()](#getPageNumber--) | 获取或设置 PSD 文件中已放置图层的页码。 |
| [getPerspective()](#getPerspective--) | 获取或设置放置在 PSD 文件中的图层的透视值。 |
| [getPerspectiveOther()](#getPerspectiveOther--) | 获取或设置放置在 PSD 文件中的图层的其他透视值。 |
| [getPlacedLayerType()](#getPlacedLayerType--) | 获取或设置放置在 PSD 文件中的图层的类型。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getRight()](#getRight--) | 获取或设置放置在 PSD 文件中的图层的右侧位置。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [getTop()](#getTop--) | 获取或设置放置在 PSD 图像中的图层的顶部位置。 |
| [getTotalPages()](#getTotalPages--) | 获取或设置放置在 PSD 文件中的图层的总页数。 |
| [getTransformMatrix()](#getTransformMatrix--) | 获取或设置放置在 PSD 文件中的图层的变换矩阵。 |
| [getUOrder()](#getUOrder--) | 获取或设置放置在 PSD 文件中的图层的 U 顺序值。 |
| [getUniqueId()](#getUniqueId--) | 获取或设置放置在 PSD 图像中的图层的全局唯一标识符。 |
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
| [get_Item(String index)](#get-Item-java.lang.String-) | 获取在指定索引处的 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)。 |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | 获取一个值，指示此实例是否具有边界单位。 |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | 获取或设置一个值，指示此实例的扭曲样式是否为自定义。 |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | 获取或设置一个值，指示此实例的旋转方向是否为水平。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将 PlLD 资源保存到指定的流容器中。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | 获取或设置 PSD 图像中已放置图层的抗锯齿策略。 |
| [setBottom(double value)](#setBottom-double-) | 获取或设置 PSD 图像中已放置图层的底部位置。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | 获取或设置 PSD 文件中已放置图层的边界。 |
| [setCustom(boolean value)](#setCustom-boolean-) | 获取或设置一个值，指示此实例的扭曲样式是否为自定义。 |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | 获取或设置分配值（如 Left、Top、Right、Bottom、TransformMatrix）的默认单位类型。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | 获取或设置水平网格点的测量单位。 |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 获取或设置扭曲项。 |
| [setLeft(double value)](#setLeft-double-) | 获取或设置 PSD 文件中已放置图层的左侧位置。 |
| [setPageNumber(int value)](#setPageNumber-int-) | 获取或设置 PSD 文件中已放置图层的页码。 |
| [setPerspective(double value)](#setPerspective-double-) | 获取或设置放置在 PSD 文件中的图层的透视值。 |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | 获取或设置放置在 PSD 文件中的图层的其他透视值。 |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | 获取或设置放置在 PSD 文件中的图层的类型。 |
| [setRight(double value)](#setRight-double-) | 获取或设置放置在 PSD 文件中的图层的右侧位置。 |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | 获取或设置一个值，指示此实例的旋转方向是否为水平。 |
| [setTop(double value)](#setTop-double-) | 获取或设置放置在 PSD 图像中的图层的顶部位置。 |
| [setTotalPages(int value)](#setTotalPages-int-) | 获取或设置放置在 PSD 文件中的图层的总页数。 |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | 获取或设置放置在 PSD 文件中的图层的变换矩阵。 |
| [setUOrder(int value)](#setUOrder-int-) | 获取或设置放置在 PSD 文件中的图层的 U 顺序值。 |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | 获取或设置放置在 PSD 图像中的图层的全局唯一标识符。 |
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
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlLdResource() {#PlLdResource--}
```
public PlLdResource()
```


初始化 [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) 类的新实例。此默认构造函数旨在供 PlLdResourceLoader 使用。使用 [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) 来创建 PlLdResource 类。

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

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


水平标识符名称

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


网格点键名称

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


方向标识符名称

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

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


common resource signature。

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

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


变换值的计数

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


类型工具信息键。

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


预期的类型值

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

### create_internalized(PlaceResourceParams plLdResourceParams) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public static PlLdResource create_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource)
### create_internalized(System.Guid uniqueId, boolean isCustom) {#create-internalized-com.aspose.ms.System.Guid-boolean-}
```
public static PlLdResource create_internalized(System.Guid uniqueId, boolean isCustom)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid |  |
| isCustom | boolean |  |

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource)
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


获取或设置 PSD 图像中已放置图层的抗锯齿策略。

值：已放置图层的抗锯齿策略。

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
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


获取或设置分配值（如 Left、Top、Right、Bottom、TransformMatrix）的默认单位类型。

值：默认测量单位类型。

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


获取或设置扭曲项。

值：扭曲项。

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


获取 PlLd 资源的字节长度。

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


获取或设置 PSD 文件中已放置图层的页码。

值：已放置图层的页码。

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
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


获取或设置放置在 PSD 文件中的图层的类型。

值：已放置图层的类型。

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


获取或设置放置在 PSD 文件中的图层的总页数。

值：已放置图层的总页数。

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


获取或设置放置在 PSD 文件中的图层的变换矩阵。

值：已放置图层的变换矩阵。

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


获取或设置放置在 PSD 图像中的图层的全局唯一标识符。

值：已放置图层的唯一标识符。

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


将 PlLD 资源保存到指定的流容器中。

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


获取或设置 PSD 图像中已放置图层的抗锯齿策略。

值：已放置图层的抗锯齿策略。

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


获取或设置扭曲项。

值：扭曲项。

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

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


获取或设置 PSD 文件中已放置图层的页码。

值：已放置图层的页码。

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

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


获取或设置放置在 PSD 文件中的图层的类型。

值：已放置图层的类型。

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


获取或设置放置在 PSD 文件中的图层的总页数。

值：已放置图层的总页数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


获取或设置放置在 PSD 文件中的图层的变换矩阵。

值：已放置图层的变换矩阵。

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


获取或设置放置在 PSD 图像中的图层的全局唯一标识符。

值：已放置图层的唯一标识符。

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

