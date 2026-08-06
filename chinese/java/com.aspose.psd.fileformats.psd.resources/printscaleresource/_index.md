---
title: "PrintScaleResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "打印比例资源"
type: docs
weight: 31
url: /zh/java/com.aspose.psd.fileformats.psd.resources/printscaleresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class PrintScaleResource extends ResourceBlock
```

打印比例资源
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PrintScaleResource()](#PrintScaleResource--) | 初始化一个新的 [PrintScaleResource](../../com.aspose.psd.fileformats.psd.resources/printscaleresource) 类的实例。 |
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
| [getScale()](#getScale--) | 获取或设置比例。 |
| [getSignature()](#getSignature--) | 获取资源签名。 |
| [getSize()](#getSize--) | 获取资源块的大小（字节），包括其数据。 |
| [getStyle()](#getStyle--) | 获取或设置样式。 |
| [getXLocation()](#getXLocation--) | 获取或设置 X 位置。 |
| [getYLocation()](#getYLocation--) | 获取或设置 Y 位置。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | 将资源块保存到指定的流中。 |
| [setID(short value)](#setID-short-) | 获取或设置资源的唯一标识符。 |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | 获取或设置图层和蒙版信息。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置资源名称。 |
| [setScale(float value)](#setScale-float-) | 获取或设置比例。 |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | 获取或设置资源块状态。 |
| [setStyle(short value)](#setStyle-short-) | 获取或设置样式。 |
| [setXLocation(float value)](#setXLocation-float-) | 获取或设置 X 位置。 |
| [setYLocation(float value)](#setYLocation-float-) | 获取或设置 Y 位置。 |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | 验证资源值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintScaleResource() {#PrintScaleResource--}
```
public PrintScaleResource()
```


初始化一个新的 [PrintScaleResource](../../com.aspose.psd.fileformats.psd.resources/printscaleresource) 类的实例。

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
### getScale() {#getScale--}
```
public final float getScale()
```


获取或设置比例。

值：比例。

**Returns:**
float
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
### getStyle() {#getStyle--}
```
public final short getStyle()
```


获取或设置样式。

值：样式。

**Returns:**
short
### getXLocation() {#getXLocation--}
```
public final float getXLocation()
```


获取或设置 X 位置。

值：X 位置。

**Returns:**
float
### getYLocation() {#getYLocation--}
```
public final float getYLocation()
```


获取或设置 Y 位置。

值：Y 位置。

**Returns:**
float
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

### setScale(float value) {#setScale-float-}
```
public final void setScale(float value)
```


获取或设置比例。

值：比例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

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

### setStyle(short value) {#setStyle-short-}
```
public final void setStyle(short value)
```


获取或设置样式。

值：样式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setXLocation(float value) {#setXLocation-float-}
```
public final void setXLocation(float value)
```


获取或设置 X 位置。

值：X 位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setYLocation(float value) {#setYLocation-float-}
```
public final void setYLocation(float value)
```


获取或设置 Y 位置。

值：Y 位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

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

