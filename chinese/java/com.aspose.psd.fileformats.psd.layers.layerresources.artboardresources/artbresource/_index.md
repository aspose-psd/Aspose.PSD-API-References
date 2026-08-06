---
title: "ArtBResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Layer.Resources 的画板信息数据/。"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtBResource extends BaseArtboardInfoResource
```

Layer.Resources 的画板信息数据（[Layer.getResources](../../com.aspose.psd.fileformats.psd.layers/layer\#getResources)/[Layer.setResources(LayerResource[])](../../com.aspose.psd.fileformats.psd.layers/layer\#setResources-LayerResource---)）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ArtBResource()](#ArtBResource--) | 初始化 [ArtBResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource) 类的新实例。 |
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
| [getArtboardBackgroundType()](#getArtboardBackgroundType--) | 获取或设置 ArtboardBackgroundType（[.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)）。 |
| [getArtboardPresetName_internalized()](#getArtboardPresetName-internalized--) | 获取或设置 ArtboardPresetName（[.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)）。 |
| [getArtboardRect_internalized()](#getArtboardRect-internalized--) | 获取或设置 ArtboardRect（[.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)）。 |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | 获取或设置资源类 ID。 |
| [getClassName_internalized()](#getClassName-internalized--) | 获取或设置资源类名称。 |
| [getColor()](#getColor--) | 获取或设置 Color（[.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)）。 |
| [getGuideIndeces_internalized()](#getGuideIndeces-internalized--) | 获取或设置 GuideIndeces（[.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)）。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getItems()](#getItems--) | 获取或设置 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 项目。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLength()](#getLength--) |    |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [getVersion_internalized()](#getVersion-internalized--) | 获取或设置资源版本。 |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将资源保存到指定的流容器。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setArtboardBackgroundType(int value)](#setArtboardBackgroundType-int-) | 获取或设置 ArtboardBackgroundType（[.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)）。 |
| [setArtboardPresetName_internalized(String value)](#setArtboardPresetName-internalized-java.lang.String-) | 获取或设置 ArtboardPresetName（[.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)）。 |
| [setArtboardRect_internalized(RectangleF value)](#setArtboardRect-internalized-com.aspose.psd.RectangleF-) | 获取或设置 ArtboardRect（[.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)）。 |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | 获取或设置资源类 ID。 |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | 获取或设置资源类名称。 |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 获取或设置 Color（[.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)）。 |
| [setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value)](#setGuideIndeces-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | 获取或设置 GuideIndeces（[.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)）。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 获取或设置 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 项目。 |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | 获取或设置资源版本。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtBResource() {#ArtBResource--}
```
public ArtBResource()
```


初始化 [ArtBResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource) 类的新实例。

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
### getArtboardBackgroundType() {#getArtboardBackgroundType--}
```
public final int getArtboardBackgroundType()
```


获取或设置 ArtboardBackgroundType（[.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)）。

**Returns:**
int
### getArtboardPresetName_internalized() {#getArtboardPresetName-internalized--}
```
public final String getArtboardPresetName_internalized()
```


获取或设置 ArtboardPresetName（[.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)）。

**Returns:**
java.lang.String
### getArtboardRect_internalized() {#getArtboardRect-internalized--}
```
public final RectangleF getArtboardRect_internalized()
```


获取或设置 ArtboardRect（[.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)）。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
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
### getColor() {#getColor--}
```
public final Color getColor()
```


获取或设置 Color（[.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)）。

**Returns:**
[Color](../../com.aspose.psd/color)
### getGuideIndeces_internalized() {#getGuideIndeces-internalized--}
```
public final System.Collections.Generic.List<OSTypeStructure> getGuideIndeces_internalized()
```


获取或设置 GuideIndeces（[.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)）。

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure>
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

### setArtboardBackgroundType(int value) {#setArtboardBackgroundType-int-}
```
public final void setArtboardBackgroundType(int value)
```


获取或设置 ArtboardBackgroundType（[.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setArtboardPresetName_internalized(String value) {#setArtboardPresetName-internalized-java.lang.String-}
```
public final void setArtboardPresetName_internalized(String value)
```


获取或设置 ArtboardPresetName（[.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setArtboardRect_internalized(RectangleF value) {#setArtboardRect-internalized-com.aspose.psd.RectangleF-}
```
public final void setArtboardRect_internalized(RectangleF value)
```


获取或设置 ArtboardRect（[.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

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

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


获取或设置 Color（[.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value) {#setGuideIndeces-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public final void setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value)
```


获取或设置 GuideIndeces（[.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

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

