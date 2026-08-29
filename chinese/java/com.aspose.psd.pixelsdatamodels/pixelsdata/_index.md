---
title: "PixelsData"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于存储图像像素数据及其边界的类。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.pixelsdatamodels/pixelsdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class PixelsData implements System.ICloneable
```

用于存储图像像素数据及其边界的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PixelsData()](#PixelsData--) | 初始化 [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) 类的新实例。 |
| [PixelsData(int[] pixels, Rectangle bounds)](#PixelsData-int---com.aspose.psd.Rectangle-) | 初始化 [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [createLoader_internalized()](#createLoader-internalized--) | 为当前的 [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) 实例创建 PixelsDataLoader 实例。 |
| [createSaver_internalized()](#createSaver-internalized--) | 为当前的 [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) 实例创建 PixelsDataSaver 实例。 |
| [deepClone()](#deepClone--) | 它创建实例的完整副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 获取或设置像素数据的边界。 |
| [getClass()](#getClass--) |  |
| [getPixels()](#getPixels--) | 获取或设置像素数据。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | 获取或设置像素数据的边界。 |
| [setPixels(int[] value)](#setPixels-int---) | 获取或设置像素数据。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PixelsData() {#PixelsData--}
```
public PixelsData()
```


初始化 [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) 类的新实例。

### PixelsData(int[] pixels, Rectangle bounds) {#PixelsData-int---com.aspose.psd.Rectangle-}
```
public PixelsData(int[] pixels, Rectangle bounds)
```


初始化 [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 像素 | int[] | 像素数据。 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 像素边界矩形。 |

### createLoader_internalized() {#createLoader-internalized--}
```
public final IRasterImageArgb32PixelLoader createLoader_internalized()
```


为当前的 [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) 实例创建 PixelsDataLoader 实例。

**Returns:**
[IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) - The new instance of PixelsDataLoader base on current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### createSaver_internalized() {#createSaver-internalized--}
```
public final IPixelsSaver createSaver_internalized()
```


为当前的 [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) 实例创建 PixelsDataSaver 实例。

**Returns:**
com.aspose.internal.IPixelsSaver - 基于当前的 [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) 实例的新 PixelsDataSaver 实例。
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


它创建实例的完整副本。

**Returns:**
java.lang.Object - 实例的副本
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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


获取或设置像素数据的边界。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPixels() {#getPixels--}
```
public final int[] getPixels()
```


获取或设置像素数据。

**Returns:**
int[]
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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


获取或设置像素数据的边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPixels(int[] value) {#setPixels-int---}
```
public final void setPixels(int[] value)
```


获取或设置像素数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

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

