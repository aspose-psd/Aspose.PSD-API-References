---
title: "PattResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "类 PattResource。"
type: docs
weight: 66
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Inheritance:**
java.lang.Object，[com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class PattResource extends LayerResource
```

类 PattResource。带有图案数据的资源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PattResource()](#PattResource--) | 初始化 [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) 类的新实例。 |
| [PattResource(int key, PattResourceData[] patterns)](#PattResource-int-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---) | 初始化 [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB header version。 |
| [PsbResourceSignature](#PsbResourceSignature) | PSB-specific resource signature。 |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD header version。 |
| [ResourceSignature](#ResourceSignature) | common resource signature。 |
| [TypeToolKey](#TypeToolKey) | ‘Patt’ 类型工具信息键，适用于 8 位。 |
| [TypeToolKey2](#TypeToolKey2) | ‘Pat2’ 类型工具信息键，适用于 16 位。 |
| [TypeToolKey3](#TypeToolKey3) | ‘Pat3’ 类型工具信息键，适用于 32 位。 |
| [ventureLicense_internalized](#ventureLicense-internalized) | venture license。 |
## Methods

| Method | 描述 |
| --- | --- |
| [addNewPattResourceData_internalized(PattResource resource)](#addNewPattResourceData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | 使用默认数据更新 Patt 资源。 |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 检查并设置资源是否为 PSB specific。 |
| [createDefaultNotEmptyResource_internalized(int bitDepth)](#createDefaultNotEmptyResource-internalized-int-) | 创建默认的非空资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLength()](#getLength--) | 获取图层资源长度（字节）。 |
| [getPatterns()](#getPatterns--) | 获取或设置图案数据； |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 保存资源块数据。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setPatterns(PattResourceData[] value)](#setPatterns-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---) | 获取或设置图案数据； |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [updateOrAddPattern_internalized(IPatternFillSettings patternSettings)](#updateOrAddPattern-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings-) | 搜索图案数据项并用新数据更新它，否则将新项添加到数组末尾。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResource() {#PattResource--}
```
public PattResource()
```


初始化 [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) 类的新实例。

### PattResource(int key, PattResourceData[] patterns) {#PattResource-int-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---}
```
public PattResource(int key, PattResourceData[] patterns)
```


初始化 [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | int | 资源类型键。 |
| patterns | [PattResourceData\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | 图案数据。 |

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


‘Patt’ 类型工具信息键，适用于 8 位。

### TypeToolKey2 {#TypeToolKey2}
```
public static final int TypeToolKey2
```


‘Pat2’ 类型工具信息键，适用于 16 位。

### TypeToolKey3 {#TypeToolKey3}
```
public static final int TypeToolKey3
```


‘Pat3’ 类型工具信息键，适用于 32 位。

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


venture license。

### addNewPattResourceData_internalized(PattResource resource) {#addNewPattResourceData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public static void addNewPattResourceData_internalized(PattResource resource)
```


使用默认数据更新 Patt 资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| resource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) | 资源。 |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


检查并设置资源是否为 PSB 特定。某些资源目前尚未被识别，但我们拥有完整的 PSB 特定资源列表，这会在保存时改变它们的行为。因此至少需要在 UnknownResource 中进行此检查。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | int | 键。 |

### createDefaultNotEmptyResource_internalized(int bitDepth) {#createDefaultNotEmptyResource-internalized-int-}
```
public static PattResource createDefaultNotEmptyResource_internalized(int bitDepth)
```


创建默认的非空资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitDepth | int |  |

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - Created [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource)
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
### getPatterns() {#getPatterns--}
```
public final PattResourceData[] getPatterns()
```


获取或设置图案数据；

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData[]
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


保存资源块数据。

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

### setPatterns(PattResourceData[] value) {#setPatterns-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---}
```
public final void setPatterns(PattResourceData[] value)
```


获取或设置图案数据；

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [PattResourceData\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) |  |

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的字符串。

**Returns:**
java.lang.String - 表示此实例的字符串。
### updateOrAddPattern_internalized(IPatternFillSettings patternSettings) {#updateOrAddPattern-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings-}
```
public final void updateOrAddPattern_internalized(IPatternFillSettings patternSettings)
```


搜索图案数据项并用新数据更新它，否则将新项添加到数组末尾。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| patternSettings | [IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings) | 用于更新图案项的图案设置对象。 |

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

