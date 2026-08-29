---
title: "LiFdDataSource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义 PSD 文件中包含嵌入文件信息的 liFD 数据源类。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFdDataSource extends LinkDataSource
```

定义 PSD 文件中包含嵌入文件信息的 liFD 数据源类。这是 PSD 文件格式操作 API 的一部分，可帮助修改 Adobe® Photoshop® 文件。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LiFdDataSource()](#LiFdDataSource--) | 初始化 [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) 类的新实例。 |
| [LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | 初始化 [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | 描述符版本。 |
| [LatestVersion_internalized](#LatestVersion-internalized) | 链接数据源的最新可用版本 |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | 意外的链接数据源类型值 |
| [ZeroChar_internalized](#ZeroChar-internalized) | 零字符 |
## Methods

| Method | 描述 |
| --- | --- |
| [create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | 获取或设置指示 PSD 资产是否被锁定的值。 |
| [getAssetModTime()](#getAssetModTime--) | 获取或设置资产的修改时间，适用于 Adobe® Photoshop® \u0421\u0421 库资产。 |
| [getChildDocId()](#getChildDocId--) | 获取或设置 Lnk2 / LnkE Adobe® Photoshop® 资源中 liFE 或 liFD 数据源的子文档标识符。 |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | 获取或设置资源类 ID。 |
| [getClassName_internalized()](#getClassName-internalized--) | 获取或设置资源类名称。 |
| [getCompId()](#getCompId--) | 获取或设置子文档当前选定的 comp 的 ID，如果未选中则为 -1。 |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | 获取或设置 ContentID 属性。 |
| [getData()](#getData--) | 获取或设置 PSD 文件中的嵌入智能对象数据。 |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | 获取嵌入数据的长度。 |
| [getDataLength_internalized()](#getDataLength-internalized--) | 获取链接源数据的长度。 |
| [getFileCreator()](#getFileCreator--) | 获取或设置 PSD 格式 LnkE / Lnk2 资源中的文件创建者。 |
| [getFileType()](#getFileType--) | 获取或设置 Adobe® Photoshop® Lnk2 / LnkE 资源所包含或链接的嵌入或外部文件的类型。 |
| [getItems_internalized()](#getItems-internalized--) | 获取或设置 定义资源属性的 OSTypeStructure 数组。 |
| [getLength()](#getLength--) | 获取链接数据源的字节长度。 |
| [getOriginalCompId()](#getOriginalCompId--) | 获取当前为子文档选择的 Comp 的原始 ID，如果未选择则为 -1。 |
| [getOriginalFileName()](#getOriginalFileName--) | 获取 Adobe® Photoshop® 全局链接资源中数据源的原始文件名。 |
| [getType()](#getType--) | 获取 Adobe® Photoshop® 全局链接数据源类型，可为以下之一或无：对应 PSD Lnk2Resource 的嵌入链接文件 liFD，对应 PSD LnkeResource 的外部链接文件 liFE，链接文件别名 liFA。 |
| [getUniqueId()](#getUniqueId--) | 获取 PSD 链接资源中数据源的全局唯一标识符。 |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | 获取或设置 位于 Items OSTypeStructures 属性之前的未知数据。 |
| [getVersion()](#getVersion--) | 获取 PSD LnkE / Lnk2 资源中数据源的版本。 |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | 获取或设置 一个值，指示此链接数据源是否具有文件打开描述符：CompId 和 OriginalCompId。 |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | 获取 一个值，指示此 PSD 链接数据源是否链接到 Adobe® Photoshop® \u0421\u0421 库项。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | 保存链接数据源块数据。 |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | 获取或设置指示 PSD 资产是否被锁定的值。 |
| [setAssetModTime(double value)](#setAssetModTime-double-) | 获取或设置资产的修改时间，适用于 Adobe® Photoshop® \u0421\u0421 库资产。 |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | 获取或设置 Lnk2 / LnkE Adobe® Photoshop® 资源中 liFE 或 liFD 数据源的子文档标识符。 |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | 获取或设置资源类 ID。 |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | 获取或设置资源类名称。 |
| [setCompId(int value)](#setCompId-int-) | 获取或设置子文档当前选定的 comp 的 ID，如果未选中则为 -1。 |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | 获取或设置 ContentID 属性。 |
| [setData(byte[] value)](#setData-byte---) | 获取或设置 PSD 文件中的嵌入智能对象数据。 |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | 获取或设置 PSD 格式 LnkE / Lnk2 资源中的文件创建者。 |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | 获取或设置 一个值，指示此链接数据源是否具有文件打开描述符：CompId 和 OriginalCompId。 |
| [setFileType(String value)](#setFileType-java.lang.String-) | 获取或设置 Adobe® Photoshop® Lnk2 / LnkE 资源所包含或链接的嵌入或外部文件的类型。 |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 获取或设置 定义资源属性的 OSTypeStructure 数组。 |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | 获取 一个值，指示此 PSD 链接数据源是否链接到 Adobe® Photoshop® \u0421\u0421 库项。 |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | 获取当前为子文档选择的 Comp 的原始 ID，如果未选择则为 -1。 |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | 获取 Adobe® Photoshop® 全局链接资源中数据源的原始文件名。 |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | 通过类型结构设置属性值。 |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | 获取 PSD 链接资源中数据源的全局唯一标识符。 |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | 获取或设置 位于 Items OSTypeStructures 属性之前的未知数据。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFdDataSource() {#LiFdDataSource--}
```
public LiFdDataSource()
```


初始化 [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) 类的新实例。

### LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


初始化 [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| version | int | 版本。 |
| uniqueId | java.util.UUID | 唯一标识符。 |
| originalFileName | java.lang.String | 原始文件的名称。 |
| fileType | java.lang.String | 文件的类型。 |
| fileCreator | java.lang.String | 文件创建者。 |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


描述符版本。

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


链接数据源的最新可用版本

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


意外的链接数据源类型值

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


零字符

### create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFdDataSource create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| version | int |  |
| GUID | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource)
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
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


获取或设置一个值，指示 PSD 资产是否被锁定。针对 Adobe® Photoshop® \u0421\u0421 Libraries 资产的锁定状态。

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


获取或设置资产的修改时间，适用于 Adobe® Photoshop® \u0421\u0421 库资产。

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


获取或设置 Lnk2 / LnkE Adobe® Photoshop® 资源中 liFE 或 liFD 数据源的子文档标识符。

**Returns:**
java.lang.String
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
### getCompId() {#getCompId--}
```
public final int getCompId()
```


获取或设置子文档当前选定 comp 的 ID，如果未选中则为 -1。Comp 是设计师可以创建的页面布局的组合。使用图层 Comp，您可以在单个 Adobe® Photoshop® 文件中创建、管理和查看布局的多个版本。图层 Comp 是图层面板状态的快照。图层 Comp 保存三种图层选项，但此属性获取用于智能对象的图层 Comp 选择标识符。智能对象中的图层 Comp

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


获取或设置 ContentID 属性。仅当 Version >= 8 时才读取和保存此属性的值。

**Returns:**
java.lang.String
### getData() {#getData--}
```
public final byte[] getData()
```


获取或设置 PSD 文件中的嵌入智能对象数据。

值：嵌入的智能对象数据。

**Returns:**
byte[]
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


获取嵌入数据的长度。

值：嵌入数据的长度。

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


获取链接源数据的长度。

**Returns:**
long - 源数据长度。
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


获取或设置 PSD 格式 LnkE / Lnk2 资源中的文件创建者。

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


获取或设置 Adobe® Photoshop® Lnk2 / LnkE 资源所包含或链接的嵌入或外部文件的类型。

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


获取或设置 定义资源属性的 OSTypeStructure 数组。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


获取链接数据源的字节长度。

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


获取子文档当前选定 Comp 的原始 ID，如果未选中则为 -1。此属性获取用于智能对象的原始图层 Comp 选择标识符。智能对象中的图层 Comp

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


获取 Adobe® Photoshop® 全局链接资源中数据源的原始文件名。

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


获取 Adobe® Photoshop® 全局链接数据源类型，可为以下之一或无：对应 PSD Lnk2Resource 的嵌入链接文件 liFD，对应 PSD LnkeResource 的外部链接文件 liFE，链接文件别名 liFA。

值：PSD 链接数据源类型。

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


获取 PSD 链接资源中数据源的全局唯一标识符。

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


获取或设置 位于 Items OSTypeStructures 属性之前的未知数据。

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


获取 PSD LnkE / Lnk2 资源中数据源的版本。

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


获取或设置 一个值，指示此链接数据源是否具有文件打开描述符：CompId 和 OriginalCompId。

值：如果此实例具有文件打开描述符则为 true；否则为 false。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


获取 一个值，指示此 PSD 链接数据源是否链接到 Adobe® Photoshop® \u0421\u0421 库项。

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


保存链接数据源块数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要保存到的流容器。 |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


获取或设置一个值，指示 PSD 资产是否被锁定。针对 Adobe® Photoshop® \u0421\u0421 Libraries 资产的锁定状态。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


获取或设置资产的修改时间，适用于 Adobe® Photoshop® \u0421\u0421 库资产。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


获取或设置 Lnk2 / LnkE Adobe® Photoshop® 资源中 liFE 或 liFD 数据源的子文档标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


获取或设置子文档当前选定 comp 的 ID，如果未选中则为 -1。Comp 是设计师可以创建的页面布局的组合。使用图层 Comp，您可以在单个 Adobe® Photoshop® 文件中创建、管理和查看布局的多个版本。图层 Comp 是图层面板状态的快照。图层 Comp 保存三种图层选项，但此属性获取用于智能对象的图层 Comp 选择标识符。智能对象中的图层 Comp

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


获取或设置 ContentID 属性。仅当 Version >= 8 时才读取和保存此属性的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


获取或设置 PSD 文件中的嵌入智能对象数据。

值：嵌入的智能对象数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


获取或设置 PSD 格式 LnkE / Lnk2 资源中的文件创建者。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


获取或设置 一个值，指示此链接数据源是否具有文件打开描述符：CompId 和 OriginalCompId。

值：如果此实例具有文件打开描述符则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


获取或设置 Adobe® Photoshop® Lnk2 / LnkE 资源所包含或链接的嵌入或外部文件的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


获取或设置 定义资源属性的 OSTypeStructure 数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


获取 一个值，指示此 PSD 链接数据源是否链接到 Adobe® Photoshop® \u0421\u0421 库项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


获取子文档当前选定 Comp 的原始 ID，如果未选中则为 -1。此属性获取用于智能对象的原始图层 Comp 选择标识符。智能对象中的图层 Comp

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


获取 Adobe® Photoshop® 全局链接资源中数据源的原始文件名。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


通过类型结构设置属性值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 结构。 |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


获取 PSD 链接资源中数据源的全局唯一标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


获取或设置 位于 Items OSTypeStructures 属性之前的未知数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

