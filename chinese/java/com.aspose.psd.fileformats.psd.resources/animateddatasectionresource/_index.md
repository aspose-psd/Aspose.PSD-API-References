---
title: "AnimatedDataSectionResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "动画数据段插件资源。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public class AnimatedDataSectionResource extends ResourceBlock
```

动画数据段插件资源。
## 字段

| 字段 | 描述 |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady 的资源签名。 |
| [ResouceBlockSignature](#ResouceBlockSignature) | 常规 Photoshop 资源签名。 |
## Methods

| Method | 描述 |
| --- | --- |
| [create_internalized()](#create-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnimatedDataSection()](#getAnimatedDataSection--) | 获取或设置动画数据段结构。 |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | 获取资源数据大小（字节）。 |
| [getID()](#getID--) | 获取或设置资源的唯一标识符。 |
| [getKeyName()](#getKeyName--) | 资源键名称。 |
| [getMinimalVersion()](#getMinimalVersion--) | 获取所需的最低 PSD 版本。 |
| [getName()](#getName--) | 获取或设置资源名称。 |
| [getSignature()](#getSignature--) | 获取资源签名。 |
| [getSize()](#getSize--) | 获取资源块的大小（字节），包括其数据。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | 将资源块保存到指定的流中。 |
| [setAnimatedDataSection_internalized(AnimatedDataSectionStructure value)](#setAnimatedDataSection-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.AnimatedDataSectionStructure-) | 获取或设置动画数据段结构。 |
| [setID(short value)](#setID-short-) | 获取或设置资源的唯一标识符。 |
| [setKeyName_internalized(String value)](#setKeyName-internalized-java.lang.String-) | 资源键名称。 |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | 获取或设置图层和蒙版信息。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置资源名称。 |
| [setRoll_internalized(RollStructure value)](#setRoll-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.RollStructure-) | 获取或设置滚动结构。 |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | 获取或设置资源块状态。 |
| [setUnknownLeftBytes_internalized(byte[] value)](#setUnknownLeftBytes-internalized-byte---) | 原始资源中的未知字节。 |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | 验证资源值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


ImageReady 的资源签名。

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


常规 Photoshop 资源签名。

### create_internalized() {#create-internalized--}
```
public static AnimatedDataSectionResource create_internalized()
```




**Returns:**
[AnimatedDataSectionResource](../../com.aspose.psd.fileformats.psd.resources/animateddatasectionresource)
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
### getAnimatedDataSection() {#getAnimatedDataSection--}
```
public final AnimatedDataSectionStructure getAnimatedDataSection()
```


获取或设置动画数据段结构。

**Returns:**
[AnimatedDataSectionStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


获取资源数据大小（字节）。

值：资源数据大小。

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


获取或设置资源的唯一标识符。

值：资源的唯一标识符。

**Returns:**
short
### getKeyName() {#getKeyName--}
```
public final String getKeyName()
```


资源键名称。

**Returns:**
java.lang.String
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


获取所需的最低 PSD 版本。

值：最小 PSD 版本。

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


获取或设置资源名称。Pascal 字符串，填充以使大小为偶数（空名称由两个字节的 0 组成）。

值：资源名称。

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


获取资源签名。应始终为 '8BIM'。

值：资源签名。

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


获取资源块的大小（字节），包括其数据。

值：资源块大小。

**Returns:**
int
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


将资源块保存到指定的流中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | 用于保存资源块的流。 |

### setAnimatedDataSection_internalized(AnimatedDataSectionStructure value) {#setAnimatedDataSection-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.AnimatedDataSectionStructure-}
```
public final void setAnimatedDataSection_internalized(AnimatedDataSectionStructure value)
```


获取或设置动画数据段结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [AnimatedDataSectionStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure) |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


获取或设置资源的唯一标识符。

值：资源的唯一标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setKeyName_internalized(String value) {#setKeyName-internalized-java.lang.String-}
```
public final void setKeyName_internalized(String value)
```


资源键名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


获取或设置图层和蒙版信息。

值：图层和蒙版信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


获取或设置资源名称。Pascal 字符串，填充以使大小为偶数（空名称由两个字节的 0 组成）。

值：资源名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setRoll_internalized(RollStructure value) {#setRoll-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.RollStructure-}
```
public final void setRoll_internalized(RollStructure value)
```


获取或设置滚动结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.layers.layerresources.RollStructure |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 签名 | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


获取或设置资源块状态。

值：资源块状态。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setUnknownLeftBytes_internalized(byte[] value) {#setUnknownLeftBytes-internalized-byte---}
```
public final void setUnknownLeftBytes_internalized(byte[] value)
```


原始资源中的未知字节。

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
### validateValues() {#validateValues--}
```
public void validateValues()
```


验证资源值。

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

