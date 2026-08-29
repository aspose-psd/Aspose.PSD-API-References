---
title: "PtFlResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "类 PtFlResource。"
type: docs
weight: 72
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.FillLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/filllayerresource)
```
public class PtFlResource extends FillLayerResource
```

类 PtFlResource。包含图案填充图层数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PtFlResource()](#PtFlResource--) | 初始化 [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource) 类的新实例。 |
| [PtFlResource(String patternName, String patternId)](#PtFlResource-java.lang.String-java.lang.String-) | 初始化 [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource) 类的新实例。 |
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
| [getAlignWithLayer()](#getAlignWithLayer--) | 获取或设置一个值，指示是否 [align with layer]。 |
| [getAngle()](#getAngle--) | 获取或设置角度。 |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLength()](#getLength--) | 获取图层资源长度（字节）。 |
| [getOffset()](#getOffset--) | 获取或设置偏移量。 |
| [getPatternId()](#getPatternId--) | 获取或设置图案标识符。 |
| [getPatternName()](#getPatternName--) | 获取或设置图案的名称。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getScale()](#getScale--) | 获取或设置比例。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [hashCode()](#hashCode--) |  |
| [isLinkedWithLayer()](#isLinkedWithLayer--) | 获取或设置一个值，指示此实例是否与图层关联。 |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将资源保存到指定的流容器。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | 获取或设置一个值，指示是否 [align with layer]。 |
| [setAngle(double value)](#setAngle-double-) | 获取或设置角度。 |
| [setClassNameAndId_internalized(String className, ClassID classID)](#setClassNameAndId-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | 设置类名和标识符。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setLinkedWithLayer(boolean value)](#setLinkedWithLayer-boolean-) | 获取或设置一个值，指示此实例是否与图层关联。 |
| [setOffset(Point value)](#setOffset-com.aspose.psd.Point-) | 获取或设置偏移量。 |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | 获取或设置图案标识符。 |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | 获取或设置图案的名称。 |
| [setScale(double value)](#setScale-double-) | 获取或设置比例。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PtFlResource() {#PtFlResource--}
```
public PtFlResource()
```


初始化 [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource) 类的新实例。

### PtFlResource(String patternName, String patternId) {#PtFlResource-java.lang.String-java.lang.String-}
```
public PtFlResource(String patternName, String patternId)
```


初始化 [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| patternName | java.lang.String | 图案的名称。 |
| patternId | java.lang.String | 模式标识符。 |

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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


获取或设置一个值，指示是否 [align with layer]。

值：如果 [align with layer] 为 true；否则为 false。

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


获取或设置角度。

值：角度。

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getOffset() {#getOffset--}
```
public final Point getOffset()
```


获取或设置偏移量。

值：偏移量。

**Returns:**
[Point](../../com.aspose.psd/point)
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


获取或设置图案标识符。

值：图案标识符。

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


获取或设置图案的名称。

值：图案的名称。

**Returns:**
java.lang.String
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
### getScale() {#getScale--}
```
public final double getScale()
```


获取或设置比例。

值：比例。

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


获取图层资源签名。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLinkedWithLayer() {#isLinkedWithLayer--}
```
public final boolean isLinkedWithLayer()
```


获取或设置一个值，指示此实例是否与图层关联。

值：如果此实例与图层关联，则为 true；否则为 false。

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

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


获取或设置一个值，指示是否 [align with layer]。

值：如果 [align with layer] 为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


获取或设置角度。

值：角度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setClassNameAndId_internalized(String className, ClassID classID) {#setClassNameAndId-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassNameAndId_internalized(String className, ClassID classID)
```


设置类名和标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| className | java.lang.String | 类的名称。 |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | 类标识符。 |

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

### setLinkedWithLayer(boolean value) {#setLinkedWithLayer-boolean-}
```
public final void setLinkedWithLayer(boolean value)
```


获取或设置一个值，指示此实例是否与图层关联。

值：如果此实例与图层关联，则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setOffset(Point value) {#setOffset-com.aspose.psd.Point-}
```
public final void setOffset(Point value)
```


获取或设置偏移量。

值：偏移量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


获取或设置图案标识符。

值：图案标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


获取或设置图案的名称。

值：图案的名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


获取或设置比例。

值：比例。

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

