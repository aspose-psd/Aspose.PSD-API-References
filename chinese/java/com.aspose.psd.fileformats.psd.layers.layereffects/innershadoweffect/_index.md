---
title: "InnerShadowEffect"
second_title: "Aspose.PSD 的 Java API 参考"
description: "内阴影图层效果"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class InnerShadowEffect implements IShadowEffect, IInternalLayerEffect
```

内阴影图层效果
## Methods

| Method | 描述 |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | 获取或设置角度（单位：度）。 |
| [getBlendMode()](#getBlendMode--) | 获取或设置混合模式。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 获取或设置颜色。 |
| [getDistance()](#getDistance--) | 获取或设置以像素为单位的距离。 |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 计算并获取基于输入图层像素边界的效果像素边界。 |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | 获取实体 |
| [getEffectType()](#getEffectType--) | 获取效果的类型 |
| [getNoise()](#getNoise--) | 获取或设置噪声。 |
| [getOpacity()](#getOpacity--) | 获取或设置不透明度。 |
| [getSize()](#getSize--) | 获取或设置以像素为单位的模糊值。 |
| [getSpread()](#getSpread--) | 获取或设置扩散（收紧）为百分比。 |
| [getUseGlobalLight()](#getUseGlobalLight--) | 获取或设置一个值，指示是否[在所有图层效果中使用此角度]。 |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | 获取或设置指示此实例是否可见的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | 获取或设置角度（单位：度）。 |
| [setBlendMode(long value)](#setBlendMode-long-) | 获取或设置混合模式。 |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 获取或设置颜色。 |
| [setDistance(int value)](#setDistance-int-) | 获取或设置以像素为单位的距离。 |
| [setNoise(int value)](#setNoise-int-) | 获取或设置噪声。 |
| [setOpacity(byte value)](#setOpacity-byte-) | 获取或设置不透明度。 |
| [setSize(int value)](#setSize-int-) | 获取或设置以像素为单位的模糊值。 |
| [setSpread(int value)](#setSpread-int-) | 获取或设置扩散（收紧）为百分比。 |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | 获取或设置一个值，指示是否[在所有图层效果中使用此角度]。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 获取或设置指示此实例是否可见的值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static InnerShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect)
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
### getAngle() {#getAngle--}
```
public final int getAngle()
```


获取或设置角度（单位：度）。

值：角度。

**Returns:**
int
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


获取或设置混合模式。

值：混合模式。

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


获取或设置颜色。

值：颜色。

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public final int getDistance()
```


获取或设置以像素为单位的距离。

值：距离。

**Returns:**
int
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


计算并获取基于输入图层像素边界的效果像素边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | 图层像素边界。 |
| globalAngle | int | 用于计算全局光角度的全局角度。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


获取实体

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


获取效果的类型

**Returns:**
int
### getNoise() {#getNoise--}
```
public final int getNoise()
```


获取或设置噪声。

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


获取或设置不透明度。

值：不透明度。

**Returns:**
byte
### getSize() {#getSize--}
```
public final int getSize()
```


获取或设置以像素为单位的模糊值。

值：大小。

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


获取或设置扩散（收紧）为百分比。

值：扩散。

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


获取或设置一个值，指示是否[在所有图层效果中使用此角度]。

值：如果[使用全局光]则为 true；否则为 false。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


获取或设置指示此实例是否可见的值。

值：  true  如果此实例可见；否则，  false .

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




### setAngle(int value) {#setAngle-int-}
```
public final void setAngle(int value)
```


获取或设置角度（单位：度）。

值：角度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


获取或设置混合模式。

值：混合模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


获取或设置颜色。

值：颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


获取或设置以像素为单位的距离。

值：距离。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


获取或设置噪声。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


获取或设置不透明度。

值：不透明度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


获取或设置以像素为单位的模糊值。

值：大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


获取或设置扩散（收紧）为百分比。

值：扩散。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


获取或设置一个值，指示是否[在所有图层效果中使用此角度]。

值：如果[使用全局光]则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


获取或设置指示此实例是否可见的值。

值：  true  如果此实例可见；否则，  false .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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

