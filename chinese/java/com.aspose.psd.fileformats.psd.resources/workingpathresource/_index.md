---
title: "WorkingPathResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "工作路径资源。"
type: docs
weight: 43
url: /zh/java/com.aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class WorkingPathResource extends ResourceBlock implements IVectorPathData
```

工作路径资源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WorkingPathResource(byte[] dataBytes)](#WorkingPathResource-byte---) | 初始化 [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource) 类的新实例。 |
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
| [getPaths()](#getPaths--) | 获取或设置路径记录。 |
| [getSignature()](#getSignature--) | 获取资源签名。 |
| [getSize()](#getSize--) | 获取资源块的大小（字节），包括其数据。 |
| [getVersion()](#getVersion--) | 获取或设置版本。 |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | 获取或设置一个值，以指示此实例是否已禁用。 |
| [isInverted()](#isInverted--) | 获取或设置一个值，以指示此实例是否已反转。 |
| [isNotLinked()](#isNotLinked--) | 获取或设置一个值，以指示此实例是否未链接。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | 将资源块保存到指定的流中。 |
| [setDisabled(boolean value)](#setDisabled-boolean-) | 获取或设置一个值，以指示此实例是否已禁用。 |
| [setID(short value)](#setID-short-) | 获取或设置资源的唯一标识符。 |
| [setInverted(boolean value)](#setInverted-boolean-) | 获取或设置一个值，以指示此实例是否已反转。 |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | 获取或设置图层和蒙版信息。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置资源名称。 |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | 获取或设置一个值，以指示此实例是否未链接。 |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | 获取或设置路径记录。 |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | 获取或设置资源块状态。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置版本。 |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | 验证资源值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WorkingPathResource(byte[] dataBytes) {#WorkingPathResource-byte---}
```
public WorkingPathResource(byte[] dataBytes)
```


初始化 [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dataBytes | byte[] | 向量路径的数据。 |

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
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


获取或设置路径记录。

Value: 路径。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
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
### getVersion() {#getVersion--}
```
public final int getVersion()
```


获取或设置版本。

值：版本。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


获取或设置一个值，以指示此实例是否已禁用。

Value:  true  如果此实例已禁用；否则为  false 。

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


获取或设置一个值，以指示此实例是否已反转。

Value:  true  如果此实例已反转；否则为  false 。

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


获取或设置一个值，以指示此实例是否未链接。

Value:  true  如果此实例未链接；否则为  false 。

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


将资源块保存到指定的流中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | 用于保存资源块的流。 |

### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


获取或设置一个值，以指示此实例是否已禁用。

Value:  true  如果此实例已禁用；否则为  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


获取或设置一个值，以指示此实例是否已反转。

Value:  true  如果此实例已反转；否则为  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


获取或设置一个值，以指示此实例是否未链接。

Value:  true  如果此实例未链接；否则为  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


获取或设置路径记录。

Value: 路径。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

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

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


获取或设置版本。

值：版本。

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

