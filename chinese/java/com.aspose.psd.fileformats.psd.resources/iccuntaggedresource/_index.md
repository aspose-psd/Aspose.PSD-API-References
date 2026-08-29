---
title: "IccUntaggedResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Icc 未标记资源"
type: docs
weight: 24
url: /zh/java/com.aspose.psd.fileformats.psd.resources/iccuntaggedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class IccUntaggedResource extends ResourceBlock
```

Icc 未标记资源
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [IccUntaggedResource()](#IccUntaggedResource--) | 初始化 [IccUntaggedResource](../../com.aspose.psd.fileformats.psd.resources/iccuntaggedresource) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady 的资源签名。 |
| [ResouceBlockSignature](#ResouceBlockSignature) | 常规 Photoshop 资源签名。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | 获取资源数据大小（字节）。 |
| [getID()](#getID--) | 获取或设置资源的唯一标识符。 |
| [getMinimalVersion()](#getMinimalVersion--) | 获取所需的最低 PSD 版本。 |
| [getName()](#getName--) | 获取或设置资源名称。 |
| [getProfile()](#getProfile--) | 获取或设置配置文件。 |
| [getSignature()](#getSignature--) | 获取资源签名。 |
| [getSize()](#getSize--) | 获取资源块的大小（字节），包括其数据。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | 将资源块保存到指定的流中。 |
| [setID(short value)](#setID-short-) | 获取或设置资源的唯一标识符。 |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | 获取或设置图层和蒙版信息。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置资源名称。 |
| [setProfile(byte value)](#setProfile-byte-) | 获取或设置配置文件。 |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | 获取或设置资源块状态。 |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | 验证资源值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IccUntaggedResource() {#IccUntaggedResource--}
```
public IccUntaggedResource()
```


初始化 [IccUntaggedResource](../../com.aspose.psd.fileformats.psd.resources/iccuntaggedresource) 类的新实例。

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
### getProfile() {#getProfile--}
```
public final byte getProfile()
```


获取或设置配置文件。

值：配置文件。

**Returns:**
byte
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

### setProfile(byte value) {#setProfile-byte-}
```
public final void setProfile(byte value)
```


获取或设置配置文件。

值：配置文件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

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

