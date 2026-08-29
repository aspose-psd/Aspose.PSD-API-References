---
title: "LayerStateEffects"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تأثيرات حالة الطبقة."
type: docs
weight: 13
url: /ar/java/com.aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Inheritance:**
java.lang.Object
```
public class LayerStateEffects
```

تأثيرات حالة الطبقة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addColorOverlay()](#addColorOverlay--) | يضيف تأثير تغطية اللون. |
| [addDropShadow()](#addDropShadow--) | يضيف تأثير الظل المتساقط. |
| [addGradientOverlay()](#addGradientOverlay--) | يضيف تأثير تغطية التدرج. |
| [addInnerShadow()](#addInnerShadow--) | يضيف تأثير الظل الداخلي. |
| [addOuterGlow()](#addOuterGlow--) | يضيف تأثير التوهج الخارجي. |
| [addPatternOverlay()](#addPatternOverlay--) | يضيف تأثير تغطية النمط. |
| [addStroke(int fillType)](#addStroke-int-) | يضيف تأثير الحد. |
| [clearLayerStyle()](#clearLayerStyle--) | يمسح جميع تأثيرات نمط الطبقة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEffects()](#getEffects--) | يحصل على تأثيرات الطبقة. |
| [getLayerStyleFX()](#getLayerStyleFX--) | يحصل أو يضبط نموذج تأثيرات نمط الطبقة. |
| [getScale()](#getScale--) | يحصل أو يضبط قيمة المقياس. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeEffectAt(int index)](#removeEffectAt-int-) | يزيل تأثير الطبقة في الفهرس المحدد. |
| [setLayerStyleFX_internalized(LayerStyleFX value)](#setLayerStyleFX-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | يحصل أو يضبط نموذج تأثيرات نمط الطبقة. |
| [setLayerStyle_internalized(LayerStyleFX layerStyle)](#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | يضبط نمط الطبقة ويحدّث قائمة التأثيرات. |
| [setScale(double value)](#setScale-double-) | يحصل أو يضبط قيمة المقياس. |
| [setVisible(boolean value)](#setVisible-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addColorOverlay() {#addColorOverlay--}
```
public final ColorOverlayEffect addColorOverlay()
```


يضيف تأثير تغطية اللون.

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) - The new instance of the [ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) class.
### addDropShadow() {#addDropShadow--}
```
public final DropShadowEffect addDropShadow()
```


يضيف تأثير الظل المتساقط.

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) - The new instance of the [DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) class.
### addGradientOverlay() {#addGradientOverlay--}
```
public final GradientOverlayEffect addGradientOverlay()
```


يضيف تأثير تغطية التدرج.

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) - The new instance of the [GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) class.
### addInnerShadow() {#addInnerShadow--}
```
public final InnerShadowEffect addInnerShadow()
```


يضيف تأثير الظل الداخلي.

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) - The new instance of the [InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) class.
### addOuterGlow() {#addOuterGlow--}
```
public final OuterGlowEffect addOuterGlow()
```


يضيف تأثير التوهج الخارجي.

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) - The new instance of the [OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) class.
### addPatternOverlay() {#addPatternOverlay--}
```
public final PatternOverlayEffect addPatternOverlay()
```


يضيف تأثير تغطية النمط.

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) - The new instance of the [PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) class.
### addStroke(int fillType) {#addStroke-int-}
```
public final StrokeEffect addStroke(int fillType)
```


يضيف تأثير الحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillType | int | نوع تعبئة الحد. |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) - The new instance of the [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) class.
### clearLayerStyle() {#clearLayerStyle--}
```
public final void clearLayerStyle()
```


يمسح جميع تأثيرات نمط الطبقة.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يحصل على تأثيرات الطبقة.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect[]
### getLayerStyleFX() {#getLayerStyleFX--}
```
public final LayerStyleFX getLayerStyleFX()
```


يحصل أو يضبط نموذج تأثيرات نمط الطبقة.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX
### getScale() {#getScale--}
```
public final double getScale()
```


يحصل أو يضبط قيمة المقياس.

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


يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية.

القيمة:  true  إذا كان هذا الكائن مرئيًا؛ وإلا،  false .

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


يزيل تأثير الطبقة في الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int | فهرس تأثير الطبقة. |

### setLayerStyleFX_internalized(LayerStyleFX value) {#setLayerStyleFX-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyleFX_internalized(LayerStyleFX value)
```


يحصل أو يضبط نموذج تأثيرات نمط الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX |  |

### setLayerStyle_internalized(LayerStyleFX layerStyle) {#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyle_internalized(LayerStyleFX layerStyle)
```


يضبط نمط الطبقة ويحدّث قائمة التأثيرات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layerStyle | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX | نمط الطبقة. |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


يحصل أو يضبط قيمة المقياس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية.

القيمة:  true  إذا كان هذا الكائن مرئيًا؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

