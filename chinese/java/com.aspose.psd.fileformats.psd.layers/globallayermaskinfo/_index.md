---
title: "GlobalLayerMaskInfo"
second_title: "Aspose.PSD 的 Java API 参考"
description: "全局图层蒙版部分。"
type: docs
weight: 15
url: /zh/java/com.aspose.psd.fileformats.psd.layers/globallayermaskinfo/
---

**Inheritance:**
java.lang.Object
```
public final class GlobalLayerMaskInfo
```

全局图层蒙版部分。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GlobalLayerMaskInfo()](#GlobalLayerMaskInfo--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaMask()](#getAlphaMask--) | 获取或设置 alpha 蒙版。 |
| [getBlueMask()](#getBlueMask--) | 获取或设置蓝色蒙版。 |
| [getClass()](#getClass--) |  |
| [getGreenMask()](#getGreenMask--) | 获取或设置绿色蒙版。 |
| [getKind()](#getKind--) | 获取或设置类型。 |
| [getLength()](#getLength--) | 获取全局图层蒙版部分的字节长度。 |
| [getOpacity()](#getOpacity--) | 获取或设置全局图层不透明度。 |
| [getOverlayColorSpace()](#getOverlayColorSpace--) | 获取或设置覆盖颜色空间（未记录的值）。 |
| [getRedMask()](#getRedMask--) | 获取或设置红色蒙版。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | 将数据保存到指定的流容器。 |
| [setAlphaMask(short value)](#setAlphaMask-short-) | 获取或设置 alpha 蒙版。 |
| [setBlueMask(short value)](#setBlueMask-short-) | 获取或设置蓝色蒙版。 |
| [setGreenMask(short value)](#setGreenMask-short-) | 获取或设置绿色蒙版。 |
| [setKind(byte value)](#setKind-byte-) | 获取或设置类型。 |
| [setOpacity(short value)](#setOpacity-short-) | 获取或设置全局图层不透明度。 |
| [setOverlayColorSpace(short value)](#setOverlayColorSpace-short-) | 获取或设置覆盖颜色空间（未记录的值）。 |
| [setRedMask(short value)](#setRedMask-short-) | 获取或设置红色蒙版。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GlobalLayerMaskInfo() {#GlobalLayerMaskInfo--}
```
public GlobalLayerMaskInfo()
```


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
### getAlphaMask() {#getAlphaMask--}
```
public final short getAlphaMask()
```


获取或设置 alpha 蒙版。

值：alpha 蒙版。

**Returns:**
short
### getBlueMask() {#getBlueMask--}
```
public final short getBlueMask()
```


获取或设置蓝色蒙版。

值：蓝色蒙版。

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGreenMask() {#getGreenMask--}
```
public final short getGreenMask()
```


获取或设置绿色蒙版。

值：绿色蒙版。

**Returns:**
short
### getKind() {#getKind--}
```
public final byte getKind()
```


获取或设置类型。0 = 选定颜色——即反转；1 = 受保护颜色；128 = 使用每个图层存储的值。此值为首选。其他值用于向后兼容 beta 版本。

值：类型。

**Returns:**
byte
### getLength() {#getLength--}
```
public final long getLength()
```


获取全局图层蒙版部分的字节长度。

**Returns:**
long
### getOpacity() {#getOpacity--}
```
public final short getOpacity()
```


获取或设置全局图层不透明度。0 = 透明，100 = 不透明。

值：全局图层不透明度。

**Returns:**
short
### getOverlayColorSpace() {#getOverlayColorSpace--}
```
public final short getOverlayColorSpace()
```


获取或设置覆盖颜色空间（未记录的值）。

值：覆盖颜色空间。

**Returns:**
short
### getRedMask() {#getRedMask--}
```
public final short getRedMask()
```


获取或设置红色蒙版。

值：红色遮罩。

**Returns:**
short
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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


将数据保存到指定的流容器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要保存到的流容器。 |

### setAlphaMask(short value) {#setAlphaMask-short-}
```
public final void setAlphaMask(short value)
```


获取或设置 alpha 蒙版。

值：alpha 蒙版。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setBlueMask(short value) {#setBlueMask-short-}
```
public final void setBlueMask(short value)
```


获取或设置蓝色蒙版。

值：蓝色蒙版。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setGreenMask(short value) {#setGreenMask-short-}
```
public final void setGreenMask(short value)
```


获取或设置绿色蒙版。

值：绿色蒙版。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setKind(byte value) {#setKind-byte-}
```
public final void setKind(byte value)
```


获取或设置类型。0 = 选定颜色——即反转；1 = 受保护颜色；128 = 使用每个图层存储的值。此值为首选。其他值用于向后兼容 beta 版本。

值：类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setOpacity(short value) {#setOpacity-short-}
```
public final void setOpacity(short value)
```


获取或设置全局图层不透明度。0 = 透明，100 = 不透明。

值：全局图层不透明度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setOverlayColorSpace(short value) {#setOverlayColorSpace-short-}
```
public final void setOverlayColorSpace(short value)
```


获取或设置覆盖颜色空间（未记录的值）。

值：覆盖颜色空间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setRedMask(short value) {#setRedMask-short-}
```
public final void setRedMask(short value)
```


获取或设置红色蒙版。

值：红色遮罩。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

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

