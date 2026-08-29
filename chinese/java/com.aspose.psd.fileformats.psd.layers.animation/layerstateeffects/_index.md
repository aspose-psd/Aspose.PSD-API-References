---
title: "LayerStateEffects"
second_title: "Aspose.PSD 的 Java API 参考"
description: "图层状态效果。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Inheritance:**
java.lang.Object
```
public class LayerStateEffects
```

图层状态效果。
## Methods

| Method | 描述 |
| --- | --- |
| [addColorOverlay()](#addColorOverlay--) | 添加颜色叠加效果。 |
| [addDropShadow()](#addDropShadow--) | 添加投影阴影效果。 |
| [addGradientOverlay()](#addGradientOverlay--) | 添加渐变叠加效果。 |
| [addInnerShadow()](#addInnerShadow--) | 添加内阴影效果。 |
| [addOuterGlow()](#addOuterGlow--) | 添加外发光效果。 |
| [addPatternOverlay()](#addPatternOverlay--) | 添加图案叠加效果。 |
| [addStroke(int fillType)](#addStroke-int-) | 添加描边效果。 |
| [clearLayerStyle()](#clearLayerStyle--) | 清除所有图层样式效果。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEffects()](#getEffects--) | 获取图层效果。 |
| [getLayerStyleFX()](#getLayerStyleFX--) | 获取或设置图层样式效果模型。 |
| [getScale()](#getScale--) | 获取或设置比例值。 |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | 获取或设置指示此实例是否可见的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeEffectAt(int index)](#removeEffectAt-int-) | 移除特定索引处的图层效果。 |
| [setLayerStyleFX_internalized(LayerStyleFX value)](#setLayerStyleFX-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | 获取或设置图层样式效果模型。 |
| [setLayerStyle_internalized(LayerStyleFX layerStyle)](#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | 设置图层样式并更新效果列表。 |
| [setScale(double value)](#setScale-double-) | 获取或设置比例值。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 获取或设置指示此实例是否可见的值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addColorOverlay() {#addColorOverlay--}
```
public final ColorOverlayEffect addColorOverlay()
```


添加颜色叠加效果。

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) - The new instance of the [ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) class.
### addDropShadow() {#addDropShadow--}
```
public final DropShadowEffect addDropShadow()
```


添加投影阴影效果。

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) - The new instance of the [DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) class.
### addGradientOverlay() {#addGradientOverlay--}
```
public final GradientOverlayEffect addGradientOverlay()
```


添加渐变叠加效果。

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) - The new instance of the [GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) class.
### addInnerShadow() {#addInnerShadow--}
```
public final InnerShadowEffect addInnerShadow()
```


添加内阴影效果。

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) - The new instance of the [InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) class.
### addOuterGlow() {#addOuterGlow--}
```
public final OuterGlowEffect addOuterGlow()
```


添加外发光效果。

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) - The new instance of the [OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) class.
### addPatternOverlay() {#addPatternOverlay--}
```
public final PatternOverlayEffect addPatternOverlay()
```


添加图案叠加效果。

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) - The new instance of the [PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) class.
### addStroke(int fillType) {#addStroke-int-}
```
public final StrokeEffect addStroke(int fillType)
```


添加描边效果。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fillType | int | 描边填充类型。 |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) - The new instance of the [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) class.
### clearLayerStyle() {#clearLayerStyle--}
```
public final void clearLayerStyle()
```


清除所有图层样式效果。

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
### getEffects() {#getEffects--}
```
public final ILayerEffect[] getEffects()
```


获取图层效果。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect[]
### getLayerStyleFX() {#getLayerStyleFX--}
```
public final LayerStyleFX getLayerStyleFX()
```


获取或设置图层样式效果模型。

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX
### getScale() {#getScale--}
```
public final double getScale()
```


获取或设置比例值。

**Returns:**
double
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




### removeEffectAt(int index) {#removeEffectAt-int-}
```
public final void removeEffectAt(int index)
```


移除特定索引处的图层效果。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| index | int | 图层效果的索引。 |

### setLayerStyleFX_internalized(LayerStyleFX value) {#setLayerStyleFX-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyleFX_internalized(LayerStyleFX value)
```


获取或设置图层样式效果模型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX |  |

### setLayerStyle_internalized(LayerStyleFX layerStyle) {#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyle_internalized(LayerStyleFX layerStyle)
```


设置图层样式并更新效果列表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layerStyle | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX | 图层样式。 |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


获取或设置比例值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

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

