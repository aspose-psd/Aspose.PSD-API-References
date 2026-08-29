---
title: "VstkResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "资源类 VstkResource。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Inheritance:**
java.lang.Object，[com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class VstkResource extends LayerResource
```

资源类 VstkResource。包含关于矢量描边数据的信息。资源应通过来自 resourcedata 的 AssignItems 方法初始化，或通过为类的属性赋值进行初始化。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VstkResource()](#VstkResource--) | 初始化 [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB header version。 |
| [PsbResourceSignature](#PsbResourceSignature) | PSB-specific resource signature。 |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD header version。 |
| [ResourceSignature](#ResourceSignature) | common resource signature。 |
| [TypeToolKey](#TypeToolKey) | 类型工具信息键。 |
| [ventureLicense_internalized](#ventureLicense-internalized) | venture license。 |
## Methods

| Method | 描述 |
| --- | --- |
| [assignItems_internalized(OSTypeStructure[] items)](#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 从 Vstk 资源分配项目结构。 |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 检查并设置资源是否为 PSB specific。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | 获取或设置 ClassID 实例。 |
| [getClassName_internalized()](#getClassName-internalized--) | 获取或设置类名。 |
| [getFillEnabled()](#getFillEnabled--) | 获取或设置指示是否启用 Stroke 填充的值。 |
| [getFillSettings()](#getFillSettings--) | 获取或设置描边的填充设置。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLength()](#getLength--) | 获取图层资源长度（字节）。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [getStrokeEnabled()](#getStrokeEnabled--) | 获取或设置指示是否启用笔画效果的值。 |
| [getStrokeStyleBlendMode()](#getStrokeStyleBlendMode--) | 获取或设置 Stroke 混合模式。 |
| [getStrokeStyleContent()](#getStrokeStyleContent--) | 获取或设置 Stroke 实体。 |
| [getStrokeStyleLineAlignment()](#getStrokeStyleLineAlignment--) | 获取或设置描边样式的线对齐方式。 |
| [getStrokeStyleLineCapType()](#getStrokeStyleLineCapType--) | 获取或设置笔画样式线帽的类型。 |
| [getStrokeStyleLineCapWidth()](#getStrokeStyleLineCapWidth--) | 获取或设置 Stroke 线帽宽度。 |
| [getStrokeStyleLineDashOffset()](#getStrokeStyleLineDashOffset--) | 获取或设置笔画样式线段偏移。 |
| [getStrokeStyleLineDashSet()](#getStrokeStyleLineDashSet--) | 获取或设置线段虚线数组。 |
| [getStrokeStyleLineJoinType()](#getStrokeStyleLineJoinType--) | 获取或设置 Stroke 样式线连接类型。 |
| [getStrokeStyleLineWidth()](#getStrokeStyleLineWidth--) | 获取或设置 Stroke 线宽。 |
| [getStrokeStyleMiterLimit()](#getStrokeStyleMiterLimit--) | 获取或设置笔画样式斜接限制。 |
| [getStrokeStyleOpacity()](#getStrokeStyleOpacity--) | 获取或设置 Stroke 样式不透明度（0-100%）。 |
| [getStrokeStyleResolution()](#getStrokeStyleResolution--) | 获取或设置 Stroke 样式分辨率。 |
| [getStrokeStyleScaleLock()](#getStrokeStyleScaleLock--) | 获取或设置 Stroke 样式比例锁定。 |
| [getStrokeStyleStrokeAdjust()](#getStrokeStyleStrokeAdjust--) | 获取或设置 Stroke 调整。 |
| [getStrokeStyleVersion()](#getStrokeStyleVersion--) | 获取或设置笔画样式版本。 |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将资源保存到指定的流容器。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | 获取或设置 ClassID 实例。 |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | 获取或设置类名。 |
| [setFillEnabled(boolean value)](#setFillEnabled-boolean-) | 获取或设置指示是否启用 Stroke 填充的值。 |
| [setFillSettings(IFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | 获取或设置描边的填充设置。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setStrokeEnabled(boolean value)](#setStrokeEnabled-boolean-) | 获取或设置指示是否启用笔画效果的值。 |
| [setStrokeStyleBlendMode(long value)](#setStrokeStyleBlendMode-long-) | 获取或设置 Stroke 混合模式。 |
| [setStrokeStyleContent(DescriptorStructure value)](#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) | 获取或设置 Stroke 实体。 |
| [setStrokeStyleLineAlignment(short value)](#setStrokeStyleLineAlignment-short-) | 获取或设置描边样式的线对齐方式。 |
| [setStrokeStyleLineCapType(short value)](#setStrokeStyleLineCapType-short-) | 获取或设置笔画样式线帽的类型。 |
| [setStrokeStyleLineCapWidth(double value)](#setStrokeStyleLineCapWidth-double-) | 获取或设置 Stroke 线帽宽度。 |
| [setStrokeStyleLineDashOffset(int value)](#setStrokeStyleLineDashOffset-int-) | 获取或设置笔画样式线段偏移。 |
| [setStrokeStyleLineDashSet(double[] value)](#setStrokeStyleLineDashSet-double---) | 获取或设置线段虚线数组。 |
| [setStrokeStyleLineJoinType(short value)](#setStrokeStyleLineJoinType-short-) | 获取或设置 Stroke 样式线连接类型。 |
| [setStrokeStyleLineWidth(double value)](#setStrokeStyleLineWidth-double-) | 获取或设置 Stroke 线宽。 |
| [setStrokeStyleMiterLimit(double value)](#setStrokeStyleMiterLimit-double-) | 获取或设置笔画样式斜接限制。 |
| [setStrokeStyleOpacity(int value)](#setStrokeStyleOpacity-int-) | 获取或设置 Stroke 样式不透明度（0-100%）。 |
| [setStrokeStyleResolution(double value)](#setStrokeStyleResolution-double-) | 获取或设置 Stroke 样式分辨率。 |
| [setStrokeStyleScaleLock(boolean value)](#setStrokeStyleScaleLock-boolean-) | 获取或设置 Stroke 样式比例锁定。 |
| [setStrokeStyleStrokeAdjust(boolean value)](#setStrokeStyleStrokeAdjust-boolean-) | 获取或设置 Stroke 调整。 |
| [setStrokeStyleVersion(int value)](#setStrokeStyleVersion-int-) | 获取或设置笔画样式版本。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VstkResource() {#VstkResource--}
```
public VstkResource()
```


初始化 [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource) 类的新实例。

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

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


common resource signature。

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


类型工具信息键。

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


venture license。

### assignItems_internalized(OSTypeStructure[] items) {#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void assignItems_internalized(OSTypeStructure[] items)
```


从 Vstk 资源分配项目结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| items | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | OSTypeStructure 实例的列表。 |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


检查并设置资源是否为 PSB 特定。某些资源目前尚未被识别，但我们拥有完整的 PSB 特定资源列表，这会在保存时改变它们的行为。因此至少需要在 UnknownResource 中进行此检查。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | int | 键。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


获取或设置 ClassID 实例。

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


获取或设置类名。

**Returns:**
java.lang.String
### getFillEnabled() {#getFillEnabled--}
```
public final boolean getFillEnabled()
```


获取或设置指示是否启用 Stroke 填充的值。

**Returns:**
boolean
### getFillSettings() {#getFillSettings--}
```
public final IFillSettings getFillSettings()
```


获取或设置描边的填充设置。

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


获取或设置标题。

值：头部。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


获取图层资源键。

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


获取图层资源长度（字节）。

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
### getSignature() {#getSignature--}
```
public int getSignature()
```


获取图层资源签名。

**Returns:**
int
### getStrokeEnabled() {#getStrokeEnabled--}
```
public final boolean getStrokeEnabled()
```


获取或设置指示是否启用笔画效果的值。

**Returns:**
boolean
### getStrokeStyleBlendMode() {#getStrokeStyleBlendMode--}
```
public final long getStrokeStyleBlendMode()
```


获取或设置 Stroke 混合模式。

**Returns:**
long
### getStrokeStyleContent() {#getStrokeStyleContent--}
```
public final DescriptorStructure getStrokeStyleContent()
```


获取或设置 Stroke 实体。属性决定笔画的填充设置。

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### getStrokeStyleLineAlignment() {#getStrokeStyleLineAlignment--}
```
public final short getStrokeStyleLineAlignment()
```


获取或设置描边样式的线对齐方式。

**Returns:**
short
### getStrokeStyleLineCapType() {#getStrokeStyleLineCapType--}
```
public final short getStrokeStyleLineCapType()
```


获取或设置笔画样式线帽的类型。

值：笔画样式线帽的类型。

**Returns:**
short
### getStrokeStyleLineCapWidth() {#getStrokeStyleLineCapWidth--}
```
public final double getStrokeStyleLineCapWidth()
```


获取或设置 Stroke 线帽宽度。

**Returns:**
double
### getStrokeStyleLineDashOffset() {#getStrokeStyleLineDashOffset--}
```
public final int getStrokeStyleLineDashOffset()
```


获取或设置笔画样式线段偏移。

值：笔画样式线段偏移。

**Returns:**
int
### getStrokeStyleLineDashSet() {#getStrokeStyleLineDashSet--}
```
public final Double[] getStrokeStyleLineDashSet()
```


获取或设置线段虚线数组。

**Returns:**
java.lang.Double[]
### getStrokeStyleLineJoinType() {#getStrokeStyleLineJoinType--}
```
public final short getStrokeStyleLineJoinType()
```


获取或设置 Stroke 样式线连接类型。

**Returns:**
short
### getStrokeStyleLineWidth() {#getStrokeStyleLineWidth--}
```
public final double getStrokeStyleLineWidth()
```


获取或设置 Stroke 线宽。

**Returns:**
double
### getStrokeStyleMiterLimit() {#getStrokeStyleMiterLimit--}
```
public final double getStrokeStyleMiterLimit()
```


获取或设置笔画样式斜接限制。

值：笔画样式斜接限制。

**Returns:**
double
### getStrokeStyleOpacity() {#getStrokeStyleOpacity--}
```
public final int getStrokeStyleOpacity()
```


获取或设置 Stroke 样式不透明度（0-100%）。

**Returns:**
int
### getStrokeStyleResolution() {#getStrokeStyleResolution--}
```
public final double getStrokeStyleResolution()
```


获取或设置 Stroke 样式分辨率。

**Returns:**
double
### getStrokeStyleScaleLock() {#getStrokeStyleScaleLock--}
```
public final boolean getStrokeStyleScaleLock()
```


获取或设置 Stroke 样式比例锁定。

**Returns:**
boolean
### getStrokeStyleStrokeAdjust() {#getStrokeStyleStrokeAdjust--}
```
public final boolean getStrokeStyleStrokeAdjust()
```


获取或设置 Stroke 调整。

**Returns:**
boolean
### getStrokeStyleVersion() {#getStrokeStyleVersion--}
```
public final int getStrokeStyleVersion()
```


获取或设置笔画样式版本。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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


将资源保存到指定的流容器。

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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


获取或设置 ClassID 实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


获取或设置类名。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFillEnabled(boolean value) {#setFillEnabled-boolean-}
```
public final void setFillEnabled(boolean value)
```


获取或设置指示是否启用 Stroke 填充的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setFillSettings(IFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillSettings(IFillSettings value)
```


获取或设置描边的填充设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

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

### setStrokeEnabled(boolean value) {#setStrokeEnabled-boolean-}
```
public final void setStrokeEnabled(boolean value)
```


获取或设置指示是否启用笔画效果的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setStrokeStyleBlendMode(long value) {#setStrokeStyleBlendMode-long-}
```
public final void setStrokeStyleBlendMode(long value)
```


获取或设置 Stroke 混合模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setStrokeStyleContent(DescriptorStructure value) {#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public final void setStrokeStyleContent(DescriptorStructure value)
```


获取或设置 Stroke 实体。属性决定笔画的填充设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

### setStrokeStyleLineAlignment(short value) {#setStrokeStyleLineAlignment-short-}
```
public final void setStrokeStyleLineAlignment(short value)
```


获取或设置描边样式的线对齐方式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setStrokeStyleLineCapType(short value) {#setStrokeStyleLineCapType-short-}
```
public final void setStrokeStyleLineCapType(short value)
```


获取或设置笔画样式线帽的类型。

值：笔画样式线帽的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setStrokeStyleLineCapWidth(double value) {#setStrokeStyleLineCapWidth-double-}
```
public final void setStrokeStyleLineCapWidth(double value)
```


获取或设置 Stroke 线帽宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setStrokeStyleLineDashOffset(int value) {#setStrokeStyleLineDashOffset-int-}
```
public final void setStrokeStyleLineDashOffset(int value)
```


获取或设置笔画样式线段偏移。

值：笔画样式线段偏移。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setStrokeStyleLineDashSet(double[] value) {#setStrokeStyleLineDashSet-double---}
```
public final void setStrokeStyleLineDashSet(double[] value)
```


获取或设置线段虚线数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setStrokeStyleLineJoinType(short value) {#setStrokeStyleLineJoinType-short-}
```
public final void setStrokeStyleLineJoinType(short value)
```


获取或设置 Stroke 样式线连接类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setStrokeStyleLineWidth(double value) {#setStrokeStyleLineWidth-double-}
```
public final void setStrokeStyleLineWidth(double value)
```


获取或设置 Stroke 线宽。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setStrokeStyleMiterLimit(double value) {#setStrokeStyleMiterLimit-double-}
```
public final void setStrokeStyleMiterLimit(double value)
```


获取或设置笔画样式斜接限制。

值：笔画样式斜接限制。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setStrokeStyleOpacity(int value) {#setStrokeStyleOpacity-int-}
```
public final void setStrokeStyleOpacity(int value)
```


获取或设置 Stroke 样式不透明度（0-100%）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setStrokeStyleResolution(double value) {#setStrokeStyleResolution-double-}
```
public final void setStrokeStyleResolution(double value)
```


获取或设置 Stroke 样式分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setStrokeStyleScaleLock(boolean value) {#setStrokeStyleScaleLock-boolean-}
```
public final void setStrokeStyleScaleLock(boolean value)
```


获取或设置 Stroke 样式比例锁定。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setStrokeStyleStrokeAdjust(boolean value) {#setStrokeStyleStrokeAdjust-boolean-}
```
public final void setStrokeStyleStrokeAdjust(boolean value)
```


获取或设置 Stroke 调整。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setStrokeStyleVersion(int value) {#setStrokeStyleVersion-int-}
```
public final void setStrokeStyleVersion(int value)
```


获取或设置笔画样式版本。

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

