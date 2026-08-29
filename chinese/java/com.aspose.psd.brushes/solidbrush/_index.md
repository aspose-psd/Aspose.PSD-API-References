---
title: "SolidBrush"
second_title: "Aspose.PSD 的 Java API 参考"
description: "实心刷旨在使用特定颜色连续绘制。"
type: docs
weight: 17
url: /zh/java/com.aspose.psd.brushes/solidbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class SolidBrush extends Brush
```

实心画笔用于使用特定颜色连续绘制。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | 初始化 SolidBrush 类的新实例。 |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.psd.Color-) | 初始化 SolidBrush 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [deepClone()](#deepClone--) | 创建当前  Brush  的深度克隆副本。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 获取或设置画笔颜色。 |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getOpacity()](#getOpacity--) | 获取画笔不透明度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 获取或设置画笔颜色。 |
| [setOpacity(float value)](#setOpacity-float-) | 设置画笔不透明度。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


初始化 SolidBrush 类的新实例。

### SolidBrush(Color color) {#SolidBrush-com.aspose.psd.Color-}
```
public SolidBrush(Color color)
```


初始化 SolidBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 实心画笔的颜色。 |

### close() {#close--}
```
public void close()
```


实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。此方法仅调用 dispose 方法。

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


创建当前  Brush  的深度克隆副本。

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


释放当前实例。

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
### getColor() {#getColor--}
```
public Color getColor()
```


获取或设置画笔颜色。

值：画笔颜色。

**Returns:**
[Color](../../com.aspose.psd/color)
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


获取指示此实例是否已释放的值。

**Returns:**
boolean -  true  如果已释放；否则，  false 。
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


获取画刷的不透明度。该值应在 0 到 1 之间。0 表示画刷完全可见，1 表示画刷完全不透明。

**Returns:**
float - 画刷不透明度值。
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




### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


获取或设置画笔颜色。

值：画笔颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 画笔不透明度的值。 |

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

