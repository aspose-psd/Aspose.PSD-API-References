---
title: "LinkResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义包含 PSD 格式图像中链接或嵌入文件信息的 LinkResource 类。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkresource/
---

**Inheritance:**
java.lang.Object，[com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public abstract class LinkResource extends LayerResource
```

定义 LinkResource 类，该类包含有关 PSD 格式图像中链接或嵌入文件的信息。链接资源可能包含多个 [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) 实例，可在任何派生类中通过索引器访问。
## 字段

| 字段 | 描述 |
| --- | --- |
| [CannotAddTheDataSourceMessage_internalized](#CannotAddTheDataSourceMessage-internalized) | “cannot add the data source” 消息 |
| [DataSourceTypeIsWrongMessage_internalized](#DataSourceTypeIsWrongMessage-internalized) | “The data source type is wrong” 消息 |
| [LengthOSourceLengthField](#LengthOSourceLengthField) | 数据源长度字段的长度。 |
| [LengthOfResourceLengthField](#LengthOfResourceLengthField) | 总资源长度字段的长度。 |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB header version。 |
| [PsbResourceSignature](#PsbResourceSignature) | PSB-specific resource signature。 |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD header version。 |
| [ResourceSignature](#ResourceSignature) | common resource signature。 |
| [ventureLicense_internalized](#ventureLicense-internalized) | venture license。 |
## Methods

| Method | 描述 |
| --- | --- |
| [addDataSource_internalized(LinkDataSource dataSource)](#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | 添加数据源。 |
| [addOrReplaceDataSource_internalized(LinkDataSource dataSource)](#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | 添加或替换数据源。 |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 检查并设置资源是否为 PSB specific。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSourceCount()](#getDataSourceCount--) | 获取可通过索引器访问的链接数据源的计数。 |
| [getDataSources_internalized()](#getDataSources-internalized--) | 获取数据源 LinkDataSource[] 数组。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLength()](#getLength--) | 获取 PSD 全局链接资源的字节长度。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [getType_internalized()](#getType-internalized--) | 获取或设置 PSD 全局链接资源类型，该类型可以是以下之一或无：对应 Lnk2Resource 和 Lnk3Resource 的嵌入式链接文件 liFD，对应 LnkeResource 的外部链接文件 liFE，链接文件别名 liFA。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的 [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)。 |
| [get_Item(UUID index)](#get-Item-java.util.UUID-) | 获取指定索引处的 [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)，它是链接数据源的唯一标识符。 |
| [get_Item_internalized(System.Guid index)](#get-Item-internalized-com.aspose.ms.System.Guid-) |  |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此链接资源实例是否为空。 |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeDataSource_internalized(System.Guid uniqueId)](#removeDataSource-internalized-com.aspose.ms.System.Guid-) | 移除链接数据源。 |
| [replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | 替换数据源。 |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 保存资源块数据。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CannotAddTheDataSourceMessage_internalized {#CannotAddTheDataSourceMessage-internalized}
```
public static final String CannotAddTheDataSourceMessage_internalized
```


“cannot add the data source” 消息

### DataSourceTypeIsWrongMessage_internalized {#DataSourceTypeIsWrongMessage-internalized}
```
public static final String DataSourceTypeIsWrongMessage_internalized
```


“The data source type is wrong” 消息

### LengthOSourceLengthField {#LengthOSourceLengthField}
```
public static final int LengthOSourceLengthField
```


数据源长度字段的长度。

### LengthOfResourceLengthField {#LengthOfResourceLengthField}
```
public static final int LengthOfResourceLengthField
```


总资源长度字段的长度。

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

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


venture license。

### addDataSource_internalized(LinkDataSource dataSource) {#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addDataSource_internalized(LinkDataSource dataSource)
```


添加数据源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | 链接数据源。 |

### addOrReplaceDataSource_internalized(LinkDataSource dataSource) {#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addOrReplaceDataSource_internalized(LinkDataSource dataSource)
```


添加或替换数据源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | 数据源。 |

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
### getDataSourceCount() {#getDataSourceCount--}
```
public final int getDataSourceCount()
```


获取可通过索引器访问的链接数据源的计数。

值：数据源计数。

**Returns:**
int
### getDataSources_internalized() {#getDataSources-internalized--}
```
public final LinkDataSource[] getDataSources_internalized()
```


获取数据源 LinkDataSource[] 数组。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource[]
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


获取 PSD 全局链接资源的字节长度。

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
### getType_internalized() {#getType-internalized--}
```
public final int getType_internalized()
```


获取或设置 PSD 全局链接资源类型，该类型可以是以下之一或无：对应 Lnk2Resource 和 Lnk3Resource 的嵌入式链接文件 liFD，对应 LnkeResource 的外部链接文件 liFE，链接文件别名 liFA。

值：PSD 链接资源类型。

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public LinkDataSource get_Item(int index)
```


获取指定索引处的 [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| index | int | 整数索引。值：该 [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)。 |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### get_Item(UUID index) {#get-Item-java.util.UUID-}
```
public final LinkDataSource get_Item(UUID index)
```


获取指定索引处的 [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)，它是链接数据源的唯一标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| index | java.util.UUID | 索引作为链接数据源的唯一标识符。值： [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)。 |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### get_Item_internalized(System.Guid index) {#get-Item-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource get_Item_internalized(System.Guid index)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| index | com.aspose.ms.System.Guid |  |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


获取一个值，指示此链接资源实例是否为空。

值：如果此链接资源为空，则为 true；否则为 false。

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




### removeDataSource_internalized(System.Guid uniqueId) {#removeDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final void removeDataSource_internalized(System.Guid uniqueId)
```


移除链接数据源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 唯一标识符。 |

### replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)
```


替换数据源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 唯一标识符。 |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | 链接数据源。 |

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

