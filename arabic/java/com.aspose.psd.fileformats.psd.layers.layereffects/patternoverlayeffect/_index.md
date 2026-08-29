---
title: "PatternOverlayEffect"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تأثير طبقة النمط"
type: docs
weight: 16
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class PatternOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

تأثير طبقة النمط
## الطرق

| طريقة | الوصف |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | يحصل أو يضبط وضع المزج. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | احسب واحصل على حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | يحصل على الكيان |
| [getEffectType()](#getEffectType--) | يحصل على نوع من نوع التأثير |
| [getOpacity()](#getOpacity--) | يحصل أو يضبط الشفافية. |
| [getSettings()](#getSettings--) | يحصل أو يضبط الإعدادات. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | يحصل أو يضبط وضع المزج. |
| [setOpacity(byte value)](#setOpacity-byte-) | يحصل أو يضبط الشفافية. |
| [setSettings(PatternFillSettings value)](#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | يحصل أو يضبط الإعدادات. |
| [setVisible(boolean value)](#setVisible-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static PatternOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect)
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


يحصل أو يضبط وضع المزج.

القيمة: وضع المزج.

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


احسب واحصل على حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود بكسلات الطبقة. |
| globalAngle | int | الزاوية العامة لحساب زاوية الضوء العامة. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


يحصل على الكيان

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


يحصل على نوع من نوع التأثير

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


يحصل أو يضبط الشفافية.

القيمة: الشفافية.

**Returns:**
byte
### getSettings() {#getSettings--}
```
public final PatternFillSettings getSettings()
```


يحصل أو يضبط الإعدادات.

القيمة: الإعدادات.

**Returns:**
[PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)
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




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


يحصل أو يضبط وضع المزج.

القيمة: وضع المزج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


يحصل أو يضبط الشفافية.

القيمة: الشفافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setSettings(PatternFillSettings value) {#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setSettings(PatternFillSettings value)
```


يحصل أو يضبط الإعدادات.

القيمة: الإعدادات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) |  |

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

