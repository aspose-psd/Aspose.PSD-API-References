---
title: "IfxsResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Ifxs 资源组图层效果资源。"
type: docs
weight: 37
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.BaseFxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/basefxresource)
```
public final class IfxsResource extends BaseFxResource
```

Ifxs 资源（组图层效果资源）
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [IfxsResource()](#IfxsResource--) | 初始化 [IfxsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ifxsresource) 类的新实例。 |
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
| [fillDefaultStructs_internalized(BaseFxResource fxResource, boolean isMultiStructure)](#fillDefaultStructs-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.BaseFxResource-boolean-) | 使用默认结构填充结构。 |
| [findResourceForTest_internalized(int type)](#findResourceForTest-internalized-int-) | 查找效果实体。 |
| [generateDefaultResource_internalized()](#generateDefaultResource-internalized--) | 生成默认资源。 |
| [getClass()](#getClass--) |  |
| [getDefaultListStructure_internalized(int multiType, int type, boolean isMultiStructure)](#getDefaultListStructure-internalized-int-int-boolean-) | 基于 LayerMultiEffectsTypes 并使用默认效果结构，创建 [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) 的新实例。 |
| [getDescriptorVersion()](#getDescriptorVersion--) | 获取描述符版本。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLayerStyle_internalized()](#getLayerStyle-internalized--) | 获取或设置图层样式。 |
| [getLength()](#getLength--) | 获取图层资源长度（字节）。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将资源保存到指定的流容器。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setLayerStyle_internalized(LayerStyleFX value)](#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | 获取或设置图层样式。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [update_internalized()](#update-internalized--) | 更新此实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IfxsResource() {#IfxsResource--}
```
public IfxsResource()
```


初始化 [IfxsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ifxsresource) 类的新实例。

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
### fillDefaultStructs_internalized(BaseFxResource fxResource, boolean isMultiStructure) {#fillDefaultStructs-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.BaseFxResource-boolean-}
```
public static void fillDefaultStructs_internalized(BaseFxResource fxResource, boolean isMultiStructure)
```


使用默认结构填充结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fxResource | [BaseFxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/basefxresource) | 任何效果资源 |
| isMultiStructure | boolean | 使用多结构类的标志 |

### findResourceForTest_internalized(int type) {#findResourceForTest-internalized-int-}
```
public final IEffectEntity findResourceForTest_internalized(int type)
```


查找效果实体。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | 类型。 |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity - 返回效果实体。
### generateDefaultResource_internalized() {#generateDefaultResource-internalized--}
```
public static IfxsResource generateDefaultResource_internalized()
```


生成默认资源。

**Returns:**
[IfxsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ifxsresource) - Generated default [IfxsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ifxsresource)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultListStructure_internalized(int multiType, int type, boolean isMultiStructure) {#getDefaultListStructure-internalized-int-int-boolean-}
```
public static ListStructure getDefaultListStructure_internalized(int multiType, int type, boolean isMultiStructure)
```


基于 LayerMultiEffectsTypes 创建 [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) 的新实例，使用默认的效果结构。如果 isMultiStructure 为 true，结构将为 Multi，否则为 Simple。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| multiType | int | 效果的多类型。 |
| type | int | 效果的类型。 |
| isMultiStructure | boolean | 使用多结构类的标志 |

**Returns:**
[ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) - The new instance of [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) based on LayerMultiEffectsTypes with default effect structures.
### getDescriptorVersion() {#getDescriptorVersion--}
```
public final int getDescriptorVersion()
```


获取描述符版本。

Value: 描述符版本。

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
### getLayerStyle_internalized() {#getLayerStyle-internalized--}
```
public final LayerStyleFX getLayerStyle_internalized()
```


获取或设置图层样式。

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX
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

### setLayerStyle_internalized(LayerStyleFX value) {#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyle_internalized(LayerStyleFX value)
```


获取或设置图层样式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX |  |

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的字符串。

**Returns:**
java.lang.String - 表示此实例的字符串。
### update_internalized() {#update-internalized--}
```
public final void update_internalized()
```


更新此实例。TODO：删除此方法。更新应自动进行。

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

