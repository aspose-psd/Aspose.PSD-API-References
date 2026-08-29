---
title: "SmartResourceCreator"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义 SmartResourceCreator 类，该类可以创建 PlLd、SoLd 和 SoLe 资源。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator/
---

**Inheritance:**
java.lang.Object
```
public class SmartResourceCreator
```

定义 SmartResourceCreator 类，可创建 PlLd、SoLd 和 SoLe 资源。用于支持 Adobe\ufffd Photoshop\ufffd 图像中的智能对象图层。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SmartResourceCreator()](#SmartResourceCreator--) | 初始化 [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) 类的新实例。 |
| [SmartResourceCreator(boolean isCustom, boolean hasCompInfo)](#SmartResourceCreator-boolean-boolean-) | 初始化 [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) 类的新实例。 |
| [SmartResourceCreator(PlacedResource template)](#SmartResourceCreator-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 使用给定模板初始化 [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generatePlacedResource()](#generatePlacedResource--) | 生成已放置的资源。 |
| [generateSmartEmbeddedResource()](#generateSmartEmbeddedResource--) | 生成嵌入的智能对象资源。 |
| [generateSmartExternalResource()](#generateSmartExternalResource--) | 生成外部智能对象资源。 |
| [getClass()](#getClass--) |  |
| [getTemplate_internalized()](#getTemplate-internalized--) | 获取或设置智能对象资源模板。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartResourceCreator() {#SmartResourceCreator--}
```
public SmartResourceCreator()
```


初始化 [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) 类的新实例。

### SmartResourceCreator(boolean isCustom, boolean hasCompInfo) {#SmartResourceCreator-boolean-boolean-}
```
public SmartResourceCreator(boolean isCustom, boolean hasCompInfo)
```


初始化 [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| isCustom | boolean | 如果设置为 true [is custom]。 |
| hasCompInfo | boolean | 如果设置为 true [has comp information]。 |

### SmartResourceCreator(PlacedResource template) {#SmartResourceCreator-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public SmartResourceCreator(PlacedResource template)
```


使用给定模板初始化 [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| template | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | 智能对象资源模板。 |

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
### generatePlacedResource() {#generatePlacedResource--}
```
public final PlLdResource generatePlacedResource()
```


生成已放置的资源。

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) - The generated [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) instance.
### generateSmartEmbeddedResource() {#generateSmartEmbeddedResource--}
```
public final SoLdResource generateSmartEmbeddedResource()
```


生成嵌入的智能对象资源。

**Returns:**
[SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource) - The generated [SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource) instance.
### generateSmartExternalResource() {#generateSmartExternalResource--}
```
public final SoLeResource generateSmartExternalResource()
```


生成外部智能对象资源。

**Returns:**
[SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) - The generated [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) instance.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getTemplate_internalized() {#getTemplate-internalized--}
```
public final SmartObjectResource getTemplate_internalized()
```


获取或设置智能对象资源模板。

值：智能对象资源模板。

**Returns:**
[SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

