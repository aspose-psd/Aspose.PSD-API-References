---
title: "BlwhResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "BlwhResource 类是黑白调整图层的资源。"
type: docs
weight: 15
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

BlwhResource 类是黑白调整图层的资源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | 初始化 [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) 类的新实例。 |
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
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | 获取或设置黑白预设文件名。 |
| [getBlues()](#getBlues--) | 获取或设置蓝色值。 |
| [getBwPresetKind()](#getBwPresetKind--) | 获取或设置黑白预设类型值。 |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | 获取或设置青色值。 |
| [getData()](#getData--) | 获取或设置数据。 |
| [getGreens()](#getGreens--) | 获取或设置绿色值。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLength()](#getLength--) | 获取图层资源长度（字节）。 |
| [getMagentas()](#getMagentas--) | 获取或设置品红值。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getReds()](#getReds--) | 获取或设置 reds 值。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [getTintColor()](#getTintColor--) | 获取 ARGB 色调颜色。 |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | 获取或设置 Blue Tint Color double 值。 |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | 获取或设置 Green Tint Color double 值。 |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | 获取或设置 Red Tint Color double 值。 |
| [getUseTint()](#getUseTint--) | 获取或设置一个值，指示是否使用 [tint color]。 |
| [getYellows()](#getYellows--) | 获取或设置 yellows 值。 |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将资源保存到指定的流容器。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | 获取或设置黑白预设文件名。 |
| [setBlues(int value)](#setBlues-int-) | 获取或设置蓝色值。 |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | 获取或设置黑白预设类型值。 |
| [setCyans(int value)](#setCyans-int-) | 获取或设置青色值。 |
| [setGreens(int value)](#setGreens-int-) | 获取或设置绿色值。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setMagentas(int value)](#setMagentas-int-) | 获取或设置品红值。 |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | 通过类型结构设置属性值。 |
| [setReds(int value)](#setReds-int-) | 获取或设置 reds 值。 |
| [setTintColor(int value)](#setTintColor-int-) | 设置色调颜色。 |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | 获取或设置 Blue Tint Color double 值。 |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | 获取或设置 Green Tint Color double 值。 |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | 获取或设置 Red Tint Color double 值。 |
| [setUseTint(boolean value)](#setUseTint-boolean-) | 获取或设置一个值，指示是否使用 [tint color]。 |
| [setYellows(int value)](#setYellows-int-) | 获取或设置 yellows 值。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


初始化 [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) 类的新实例。

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


获取或设置黑白预设文件名。

值：黑白预设文件名。

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


获取或设置蓝色值。

值：blues 值。

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


获取或设置黑白预设类型值。

值：黑白预设类型值。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


获取或设置青色值。

值：cyans 值。

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


获取或设置数据。

值：数据。

**Returns:**
byte[]
### getGreens() {#getGreens--}
```
public final int getGreens()
```


获取或设置绿色值。

值：greens 值。

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
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


获取或设置品红值。

值：magentas 值。

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
### getReds() {#getReds--}
```
public final int getReds()
```


获取或设置 reds 值。

值：reds 值。

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


获取图层资源签名。

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


获取 ARGB 色调颜色。

**Returns:**
int - ARGB 色调颜色。
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


获取或设置 Blue Tint Color double 值。

值：Blue Tint Color double 值。

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


获取或设置 Green Tint Color double 值。

值：Green Tint Color double 值。

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


获取或设置 Red Tint Color double 值。

值：Red Tint Color double 值。

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


获取或设置一个值，指示是否使用 [tint color]。

值：如果使用 [tint color] 则为 true；否则为 false。

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


获取或设置 yellows 值。

值：yellows 值。

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

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


获取或设置黑白预设文件名。

值：黑白预设文件名。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


获取或设置蓝色值。

值：blues 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


获取或设置黑白预设类型值。

值：黑白预设类型值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


获取或设置青色值。

值：cyans 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


获取或设置绿色值。

值：greens 值。

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


获取或设置品红值。

值：magentas 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


通过类型结构设置属性值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 结构。 |

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


获取或设置 reds 值。

值：reds 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


设置色调颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 该值。 |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


获取或设置 Blue Tint Color double 值。

值：Blue Tint Color double 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


获取或设置 Green Tint Color double 值。

值：Green Tint Color double 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


获取或设置 Red Tint Color double 值。

值：Red Tint Color double 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


获取或设置一个值，指示是否使用 [tint color]。

值：如果使用 [tint color] 则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


获取或设置 yellows 值。

值：yellows 值。

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

