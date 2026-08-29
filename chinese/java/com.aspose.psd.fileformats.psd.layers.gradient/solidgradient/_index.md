---
title: "SolidGradient"
second_title: "Aspose.PSD 的 Java API 参考"
description: "渐变填充效果设置。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

渐变填充效果设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | 初始化 [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | 添加颜色点。 |
| [addTransparencyPoint()](#addTransparencyPoint--) | 添加颜色点。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | 生成 LFX2 资源节点。 |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | 获取或设置颜色点。 |
| [getGradientMode()](#getGradientMode--) | 获取此渐变的模式。 |
| [getGradientName()](#getGradientName--) | 获取或设置渐变的名称。 |
| [getInterpolation()](#getInterpolation--) | 获取或设置插值。 |
| [getTransparencyPoints()](#getTransparencyPoints--) | 获取或设置透明度点。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | 移除颜色点。 |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | 移除透明点。 |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | 获取或设置颜色点。 |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 获取或设置渐变的名称。 |
| [setInterpolation(short value)](#setInterpolation-short-) | 获取或设置插值。 |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | 获取或设置透明度点。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


初始化 [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) 类的新实例。

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


添加颜色点。

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


添加颜色点。

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


生成 LFX2 资源节点。

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - 生成的 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 列表
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


获取或设置颜色点。

值：颜色点。

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


获取此渐变的模式。确定“Gradient Type” = “Solid/Noise”（0/1）。

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


获取或设置渐变的名称。

值：渐变的名称。

**Returns:**
java.lang.String
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


获取或设置插值。确定平滑度，当 'Gradient Type' = 'Solid' 时。取值范围：0-4096。

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


获取或设置透明度点。

值：透明点。

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
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




### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


移除颜色点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | 该点。 |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


移除透明点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | 该点。 |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


获取或设置颜色点。

值：颜色点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


获取或设置渐变的名称。

值：渐变的名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


获取或设置插值。确定平滑度，当 'Gradient Type' = 'Solid' 时。取值范围：0-4096。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


获取或设置透明度点。

值：透明点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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

