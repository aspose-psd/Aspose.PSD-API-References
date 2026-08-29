---
title: "GradientColorPoint"
second_title: "Aspose.PSD 的 Java API 参考"
description: "渐变颜色点。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint)
```
public class GradientColorPoint implements IGradientColorPoint
```

渐变颜色点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GradientColorPoint()](#GradientColorPoint--) | 初始化一个新的 [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) 类实例。 |
| [GradientColorPoint(Color color, int location, int medianPointLocation)](#GradientColorPoint-com.aspose.psd.Color-int-int-) | 初始化一个新的 [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) 类实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [create_internalized(GradientColorPointEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | 颜色遵循的模式 |
| [getLocation()](#getLocation--) | 获取或设置渐变上的点位置。 |
| [getMedianPointLocation()](#getMedianPointLocation--) | 获取或设置中位渐变点的位置。 |
| [getRawColor()](#getRawColor--) | 获取或设置原始颜色。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorMode(short value)](#setColorMode-short-) | 颜色遵循的模式 |
| [setLocation(int value)](#setLocation-int-) | 获取或设置渐变上的点位置。 |
| [setMedianPointLocation(int value)](#setMedianPointLocation-int-) | 获取或设置中位渐变点的位置。 |
| [setRawColor(RawColor value)](#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 获取或设置原始颜色。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientColorPoint() {#GradientColorPoint--}
```
public GradientColorPoint()
```


初始化一个新的 [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) 类实例。

### GradientColorPoint(Color color, int location, int medianPointLocation) {#GradientColorPoint-com.aspose.psd.Color-int-int-}
```
public GradientColorPoint(Color color, int location, int medianPointLocation)
```


初始化一个新的 [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 渐变上的颜色点。 |
| location | int | 渐变上颜色点的位置。 |
| medianPointLocation | int | 中位渐变点的位置。 |

### create_internalized(GradientColorPointEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity-}
```
public static GradientColorPoint create_internalized(GradientColorPointEntity entity)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity |  |

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint)
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
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


颜色遵循的模式

**Returns:**
short
### getLocation() {#getLocation--}
```
public final int getLocation()
```


获取或设置渐变上的点位置。

值：位置。

**Returns:**
int
### getMedianPointLocation() {#getMedianPointLocation--}
```
public final int getMedianPointLocation()
```


获取或设置中位渐变点的位置。

值：中点位置。

**Returns:**
int
### getRawColor() {#getRawColor--}
```
public final RawColor getRawColor()
```


获取或设置原始颜色。

值：原始颜色。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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




### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


颜色遵循的模式

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setLocation(int value) {#setLocation-int-}
```
public final void setLocation(int value)
```


获取或设置渐变上的点位置。

值：位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMedianPointLocation(int value) {#setMedianPointLocation-int-}
```
public final void setMedianPointLocation(int value)
```


获取或设置中位渐变点的位置。

值：中点位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRawColor(RawColor value) {#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setRawColor(RawColor value)
```


获取或设置原始颜色。

值：原始颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

