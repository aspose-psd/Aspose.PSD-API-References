---
title: "StrokeEffect"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Adobe Photoshop 对 PSD 图层的描边效果。"
type: docs
weight: 17
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

Adobe® Photoshop® 对 PSD 图层的描边效果。
## Methods

| Method | 描述 |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | 获取或设置混合模式。 |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 计算并获取基于输入图层像素边界的效果像素边界。 |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | 获取实体 |
| [getEffectType()](#getEffectType--) | 获取效果的类型 |
| [getFillSettings()](#getFillSettings--) | 获取或设置填充设置。 |
| [getOpacity()](#getOpacity--) | 获取或设置不透明度。 |
| [getOverprint()](#getOverprint--) | 获取或设置一个值，指示此 [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) 是否会将描边与当前图层内容混合。 |
| [getPosition()](#getPosition--) | 获取或设置描边效果的位置，以控制描边相对于 PSD 图层内容的对齐方式。 |
| [getSize()](#getSize--) | 获取或设置描边效果的宽度。 |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | 获取或设置指示此实例是否可见的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | 获取或设置混合模式。 |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | 获取或设置填充设置。 |
| [setOpacity(byte value)](#setOpacity-byte-) | 获取或设置不透明度。 |
| [setOverprint(boolean value)](#setOverprint-boolean-) | 获取或设置一个值，指示此 [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) 是否会将描边与当前图层内容混合。 |
| [setPosition(short value)](#setPosition-short-) | 获取或设置描边效果的位置，以控制描边相对于 PSD 图层内容的对齐方式。 |
| [setSize(int value)](#setSize-int-) | 获取或设置描边效果的宽度。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 获取或设置指示此实例是否可见的值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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


获取效果的类型

**Returns:**
int
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


获取或设置填充设置。

值： 填充设置。

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


获取或设置不透明度。

值：不透明度。

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


获取或设置一个值，指示此 [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) 是否会将描边与当前图层内容混合。

值：  true  如果必须将描边与当前图层内容混合；否则，  false 。

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


获取或设置描边效果的位置，以控制描边相对于 PSD 图层内容的对齐方式。该值可以是 [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) 以在 PSD 图层内容内部绘制描边，或 [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) 以在 PSD 图层内容外围绘制描边，且 [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) 以在内部和外部同时绘制描边。

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


获取或设置描边效果的宽度。

值： 描边效果的宽度。

**Returns:**
int
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

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


获取或设置填充设置。

值： 填充设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

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

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


获取或设置一个值，指示此 [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) 是否会将描边与当前图层内容混合。

值：  true  如果必须将描边与当前图层内容混合；否则，  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


获取或设置描边效果的位置，以控制描边相对于 PSD 图层内容的对齐方式。该值可以是 [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) 以在 PSD 图层内容内部绘制描边，或 [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) 以在 PSD 图层内容外围绘制描边，且 [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) 以在内部和外部同时绘制描边。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


获取或设置描边效果的宽度。

值： 描边效果的宽度。

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

