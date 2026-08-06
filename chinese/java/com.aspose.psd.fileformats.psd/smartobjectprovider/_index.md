---
title: "SmartObjectProvider"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义智能对象提供程序，提供从 PSD 文件的全局链接资源及其内容中获取/设置数据源的功能。"
type: docs
weight: 17
url: /zh/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

定义智能对象提供程序，提供从 PSD 文件的全局链接资源及其内容中获取/设置数据源的功能。
## Methods

| Method | 描述 |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | 将图层转换为嵌入式智能对象。 |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | 将图层转换为嵌入式智能对象。 |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | 初始化一个新的 [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) 类的实例。 |
| [embedAllLinked()](#embedAllLinked--) | 在图像中嵌入所有已链接的智能对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | 获取智能对象图层内容的类型。 |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | 获取嵌入或链接的文件内容。 |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | 通过唯一 ID 获取链接数据源。 |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | 加载内容。 |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | 通过复制源图层创建新的智能对象图层。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | 从嵌入和外部资源中移除未在提供的有效 GUID 列表中出现的数据源。 |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | 用提供的内容替换全局资源中的数据源以进行嵌入。 |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | 用来自外部文件的新创建的数据源替换全局 LinkResource 资源中的数据源。 |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | 设置嵌入或外部文件的内容。 |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | 在全局链接资源中设置（替换或添加）链接数据源。 |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | 更新图像中所有已修改智能对象的内容。 |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | 更新容器中所有唯一 ID 与 oldGuid 匹配的智能对象图层。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


将图层转换为嵌入式智能对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | 图层。 |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


将图层转换为嵌入式智能对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layerNumbers | int[] | 图层编号。 |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


初始化一个新的 [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) 类的实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | 容器。 |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


在图像中嵌入所有已链接的智能对象。

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
### getContentType_internalized(System.Guid uniqueId) {#getContentType-internalized-com.aspose.ms.System.Guid-}
```
public final int getContentType_internalized(System.Guid uniqueId)
```


获取智能对象图层内容的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 唯一标识符。 |

**Returns:**
int - 智能对象图层内容的类型。
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


获取嵌入或链接的文件内容。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 链接数据源的唯一标识符。 |

**Returns:**
byte[] - byte[] 内容。
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


通过唯一 ID 获取链接数据源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 唯一标识符。 |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadContents_internalized(System.Guid uniqueId, LoadOptions options) {#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-}
```
public final Image loadContents_internalized(System.Guid uniqueId, LoadOptions options)
```


加载内容。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 唯一标识符。 |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


通过复制源图层创建新的智能对象图层。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | 源图层。 |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources) {#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--}
```
public final void removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)
```


从嵌入的和外部资源中移除未出现在提供的有效 GUID 列表中的数据源。此方法通过与当前有效的数据源标识符进行比较来清理孤立的数据源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | 要保留的有效数据源 GUID 列表。不在此列表中的数据源将被移除。 |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


用提供的内容替换全局资源中的数据源以进行嵌入。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | 现有数据源的唯一标识符。 |
| contents | byte[] | 新数据源的数据。 |

**Returns:**
com.aspose.ms.System.Guid - 已创建的嵌入式数据源的唯一标识符。 LiFdDataSource 。
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


用来自外部文件的新创建的数据源替换全局 LinkResource 资源中的数据源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | 已放置的资源。 |
| linkedPath | java.lang.String | 链接文件的绝对路径。 |
| isReplaceOnlyThis | boolean | 如果为 true，则不移除全局资源中的数据源。 |

**Returns:**
com.aspose.ms.System.Guid - 已创建的链接数据源的唯一标识符 Guid。 [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource)。
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


设置嵌入或外部文件的内容。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 链接数据源的唯一标识符。 |
| data | byte[] | 数据。 |
| fileType | java.lang.String | 数据文件类型。 |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


在全局链接资源中设置（替换或添加）链接数据源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | 链接数据源。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAllModifiedContent() {#updateAllModifiedContent--}
```
public final void updateAllModifiedContent()
```


更新图像中所有已修改智能对象的内容。

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


更新容器中所有 UniqueId 与 oldGuid 匹配的智能对象图层。匹配的图层 UniqueId 将重新分配为 newGuid，并刷新其内容。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | 要替换的原始智能对象数据源的唯一标识符。 |
| newGuid | com.aspose.ms.System.Guid | 要分配的新智能对象数据源的唯一标识符。 |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | 更新内容时要应用的分辨率设置。如果为 null，则使用图像分辨率。 |

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

