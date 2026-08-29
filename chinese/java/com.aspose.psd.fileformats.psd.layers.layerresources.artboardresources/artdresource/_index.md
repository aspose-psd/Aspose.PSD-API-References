---
title: "ArtDResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "PsdImage.GlobalLayerResources/ 的画板信息数据。"
type: docs
weight: 12
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtDResource extends BaseArtboardInfoResource
```

PsdImage.GlobalLayerResources 的画板信息数据（[PsdImage.getGlobalLayerResources](../../com.aspose.psd.fileformats.psd/psdimage\#getGlobalLayerResources)/[PsdImage.setGlobalLayerResources(LayerResource[])](../../com.aspose.psd.fileformats.psd/psdimage\#setGlobalLayerResources-LayerResource---)）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ArtDResource()](#ArtDResource--) | 初始化 [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource) 类的新实例。 |
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
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 检查并设置资源是否为 PSB specific。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArtboardCount_internalized()](#getArtboardCount-internalized--) | 获取或设置 Art-boards 的计数。 |
| [getAutoExpandOffset_internalized()](#getAutoExpandOffset-internalized--) | 获取或设置自动展开偏移量。 |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | 获取或设置资源类 ID。 |
| [getClassName_internalized()](#getClassName-internalized--) | 获取或设置资源类名称。 |
| [getDocDefaultNewArtboardBackgroundColor_internalized()](#getDocDefaultNewArtboardBackgroundColor-internalized--) | 获取或设置 DocDefaultNewArtboardBackgroundColor（[.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)）。 |
| [getDocDefaultNewArtboardBackgroundType_internalized()](#getDocDefaultNewArtboardBackgroundType-internalized--) | 获取或设置 DocDefaultNewArtboardBackgroundType（[.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)）。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getItems()](#getItems--) | 获取或设置 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 项目。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLength()](#getLength--) |    |
| [getOriginPoint_internalized()](#getOriginPoint-internalized--) | 获取或设置原点。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [getVersion_internalized()](#getVersion-internalized--) | 获取或设置资源版本。 |
| [hashCode()](#hashCode--) |  |
| [isAutoExpandEnabled_internalized()](#isAutoExpandEnabled-internalized--) | 获取或设置 IsAutoExpandEnabled（[.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)）。 |
| [isAutoNestEnabled_internalized()](#isAutoNestEnabled-internalized--) | 获取或设置 IsAutoNestEnabled（[.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)）。 |
| [isAutoPositionEnabled_internalized()](#isAutoPositionEnabled-internalized--) | 获取或设置 IsAutoPositionEnabled（[.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)）。 |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [isShrinkwrapOnSaveEnabled_internalized()](#isShrinkwrapOnSaveEnabled-internalized--) | 获取或设置 IsShrinkwrapOnSaveEnabled（[.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)）。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将资源保存到指定的流容器。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setArtboardCount_internalized(int value)](#setArtboardCount-internalized-int-) | 获取或设置 Art-boards 的计数。 |
| [setAutoExpandEnabled_internalized(boolean value)](#setAutoExpandEnabled-internalized-boolean-) | 获取或设置 IsAutoExpandEnabled（[.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)）。 |
| [setAutoExpandOffset_internalized(PointF value)](#setAutoExpandOffset-internalized-com.aspose.psd.PointF-) | 获取或设置自动展开偏移量。 |
| [setAutoNestEnabled_internalized(boolean value)](#setAutoNestEnabled-internalized-boolean-) | 获取或设置 IsAutoNestEnabled（[.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)）。 |
| [setAutoPositionEnabled_internalized(boolean value)](#setAutoPositionEnabled-internalized-boolean-) | 获取或设置 IsAutoPositionEnabled（[.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)）。 |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | 获取或设置资源类 ID。 |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | 获取或设置资源类名称。 |
| [setDocDefaultNewArtboardBackgroundColor_internalized(Color value)](#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-) | 获取或设置 DocDefaultNewArtboardBackgroundColor（[.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)）。 |
| [setDocDefaultNewArtboardBackgroundType_internalized(int value)](#setDocDefaultNewArtboardBackgroundType-internalized-int-) | 获取或设置 DocDefaultNewArtboardBackgroundType（[.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)）。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 获取或设置 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 项目。 |
| [setOriginPoint_internalized(PointF value)](#setOriginPoint-internalized-com.aspose.psd.PointF-) | 获取或设置原点。 |
| [setShrinkwrapOnSaveEnabled_internalized(boolean value)](#setShrinkwrapOnSaveEnabled-internalized-boolean-) | 获取或设置 IsShrinkwrapOnSaveEnabled（[.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)）。 |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | 获取或设置资源版本。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtDResource() {#ArtDResource--}
```
public ArtDResource()
```


初始化 [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource) 类的新实例。

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
### getArtboardCount_internalized() {#getArtboardCount-internalized--}
```
public final int getArtboardCount_internalized()
```


获取或设置 Art-boards 的计数。

**Returns:**
int
### getAutoExpandOffset_internalized() {#getAutoExpandOffset-internalized--}
```
public final PointF getAutoExpandOffset_internalized()
```


获取或设置自动展开偏移量。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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


获取或设置资源类 ID。

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


获取或设置资源类名称。

**Returns:**
java.lang.String
### getDocDefaultNewArtboardBackgroundColor_internalized() {#getDocDefaultNewArtboardBackgroundColor-internalized--}
```
public final Color getDocDefaultNewArtboardBackgroundColor_internalized()
```


获取或设置 DocDefaultNewArtboardBackgroundColor（[.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)）。

**Returns:**
[Color](../../com.aspose.psd/color)
### getDocDefaultNewArtboardBackgroundType_internalized() {#getDocDefaultNewArtboardBackgroundType-internalized--}
```
public final int getDocDefaultNewArtboardBackgroundType_internalized()
```


获取或设置 DocDefaultNewArtboardBackgroundType（[.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)）。

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
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


获取或设置 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 项目。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
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


  

**Returns:**
int
### getOriginPoint_internalized() {#getOriginPoint-internalized--}
```
public final PointF getOriginPoint_internalized()
```


获取或设置原点。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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
### getVersion_internalized() {#getVersion-internalized--}
```
public final int getVersion_internalized()
```


获取或设置资源版本。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoExpandEnabled_internalized() {#isAutoExpandEnabled-internalized--}
```
public final boolean isAutoExpandEnabled_internalized()
```


获取或设置 IsAutoExpandEnabled（[.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)）。

**Returns:**
boolean
### isAutoNestEnabled_internalized() {#isAutoNestEnabled-internalized--}
```
public final boolean isAutoNestEnabled_internalized()
```


获取或设置 IsAutoNestEnabled（[.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)）。

**Returns:**
boolean
### isAutoPositionEnabled_internalized() {#isAutoPositionEnabled-internalized--}
```
public final boolean isAutoPositionEnabled_internalized()
```


获取或设置 IsAutoPositionEnabled（[.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)）。

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
### isShrinkwrapOnSaveEnabled_internalized() {#isShrinkwrapOnSaveEnabled-internalized--}
```
public final boolean isShrinkwrapOnSaveEnabled_internalized()
```


获取或设置 IsShrinkwrapOnSaveEnabled（[.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)）。

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

### setArtboardCount_internalized(int value) {#setArtboardCount-internalized-int-}
```
public final void setArtboardCount_internalized(int value)
```


获取或设置 Art-boards 的计数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setAutoExpandEnabled_internalized(boolean value) {#setAutoExpandEnabled-internalized-boolean-}
```
public final void setAutoExpandEnabled_internalized(boolean value)
```


获取或设置 IsAutoExpandEnabled（[.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setAutoExpandOffset_internalized(PointF value) {#setAutoExpandOffset-internalized-com.aspose.psd.PointF-}
```
public final void setAutoExpandOffset_internalized(PointF value)
```


获取或设置自动展开偏移量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setAutoNestEnabled_internalized(boolean value) {#setAutoNestEnabled-internalized-boolean-}
```
public final void setAutoNestEnabled_internalized(boolean value)
```


获取或设置 IsAutoNestEnabled（[.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setAutoPositionEnabled_internalized(boolean value) {#setAutoPositionEnabled-internalized-boolean-}
```
public final void setAutoPositionEnabled_internalized(boolean value)
```


获取或设置 IsAutoPositionEnabled（[.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


获取或设置资源类 ID。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


获取或设置资源类名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDocDefaultNewArtboardBackgroundColor_internalized(Color value) {#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-}
```
public final void setDocDefaultNewArtboardBackgroundColor_internalized(Color value)
```


获取或设置 DocDefaultNewArtboardBackgroundColor（[.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDocDefaultNewArtboardBackgroundType_internalized(int value) {#setDocDefaultNewArtboardBackgroundType-internalized-int-}
```
public final void setDocDefaultNewArtboardBackgroundType_internalized(int value)
```


获取或设置 DocDefaultNewArtboardBackgroundType（[.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)）。

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

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


获取或设置 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 项目。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setOriginPoint_internalized(PointF value) {#setOriginPoint-internalized-com.aspose.psd.PointF-}
```
public final void setOriginPoint_internalized(PointF value)
```


获取或设置原点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setShrinkwrapOnSaveEnabled_internalized(boolean value) {#setShrinkwrapOnSaveEnabled-internalized-boolean-}
```
public final void setShrinkwrapOnSaveEnabled_internalized(boolean value)
```


获取或设置 IsShrinkwrapOnSaveEnabled（[.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


获取或设置资源版本。

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

