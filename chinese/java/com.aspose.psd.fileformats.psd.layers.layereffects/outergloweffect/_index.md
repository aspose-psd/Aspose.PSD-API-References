---
title: "OuterGlowEffect"
second_title: "Aspose.PSD 的 Java API 参考"
description: "外发光图层效果"
type: docs
weight: 15
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

外发光图层效果
## Methods

| Method | 描述 |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | 获取或设置混合模式。 |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 计算并获取基于输入图层像素边界的效果像素边界。 |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | 获取实体 |
| [getEffectType()](#getEffectType--) | 获取效果类型 |
| [getFillColor()](#getFillColor--) | 获取或设置颜色。 |
| [getIntensity()](#getIntensity--) | 获取或设置角度（单位：度）。 |
| [getJitter()](#getJitter--) | 获取或设置噪声。 |
| [getNoise()](#getNoise--) | 获取或设置噪声。 |
| [getOpacity()](#getOpacity--) | 获取或设置不透明度。 |
| [getRange()](#getRange--) | 获取或设置噪声。 |
| [getSize()](#getSize--) | 获取以像素为单位的模糊值。 |
| [getSpread()](#getSpread--) | 获取或设置以百分比表示的强度。 |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | 获取或设置已启用的 AntiAliasing 效果 |
| [isSoftBlend()](#isSoftBlend--) | 获取或设置一个值，指示是否 [knocks out]。 |
| [isVisible()](#isVisible--) | 获取或设置指示此实例是否可见的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | 获取或设置已启用的 AntiAliasing 效果 |
| [setBlendMode(long value)](#setBlendMode-long-) | 获取或设置混合模式。 |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | 获取或设置颜色。 |
| [setIntensity(int value)](#setIntensity-int-) | 获取或设置角度（单位：度）。 |
| [setJitter(int value)](#setJitter-int-) | 获取或设置噪声。 |
| [setNoise(int value)](#setNoise-int-) | 获取或设置噪声。 |
| [setOpacity(byte value)](#setOpacity-byte-) | 获取或设置不透明度。 |
| [setRange(int value)](#setRange-int-) | 获取或设置噪声。 |
| [setSize(int value)](#setSize-int-) | 获取以像素为单位的模糊值。 |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | 获取或设置一个值，指示是否 [knocks out]。 |
| [setSpread(int value)](#setSpread-int-) | 获取或设置以百分比表示的强度。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 获取或设置指示此实例是否可见的值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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


获取效果类型

**Returns:**
int
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


获取或设置颜色。

值：颜色。

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


获取或设置角度（单位：度）。

值：角度。

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


获取或设置噪声。

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
### getRange() {#getRange--}
```
public final int getRange()
```


获取或设置噪声。

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


获取以像素为单位的模糊值。

值：大小。

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


获取或设置以百分比表示的强度。

值：扩散。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAntiAliasing() {#isAntiAliasing--}
```
public final boolean isAntiAliasing()
```


获取或设置已启用的 AntiAliasing 效果

值：距离。

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


获取或设置一个值，指示是否 [knocks out]。

值：  true  如果 [knocks out]；否则，  false 。

**Returns:**
boolean
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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


获取或设置已启用的 AntiAliasing 效果

值：距离。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


获取或设置颜色。

值：颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


获取或设置角度（单位：度）。

值：角度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


获取或设置噪声。

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

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


获取或设置噪声。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


获取以像素为单位的模糊值。

值：大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


获取或设置一个值，指示是否 [knocks out]。

值：  true  如果 [knocks out]；否则，  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


获取或设置以百分比表示的强度。

值：扩散。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

