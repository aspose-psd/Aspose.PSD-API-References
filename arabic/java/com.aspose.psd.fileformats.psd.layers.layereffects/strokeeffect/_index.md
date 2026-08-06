---
title: "StrokeEffect"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تأثير الخط في Adobe Photoshop لطبقة PSD."
type: docs
weight: 17
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

تأثير الخط في Adobe® Photoshop® لطبقة PSD.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | يحصل أو يضبط وضع المزج. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | احسب واحصل على حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | يحصل على الكيان |
| [getEffectType()](#getEffectType--) | يحصل على نوع التأثير |
| [getFillSettings()](#getFillSettings--) | يحصل أو يضبط إعدادات التعبئة. |
| [getOpacity()](#getOpacity--) | يحصل أو يضبط الشفافية. |
| [getOverprint()](#getOverprint--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) سيخلط الخط مع محتويات الطبقة الحالية. |
| [getPosition()](#getPosition--) | يحصل أو يضبط موضع تأثير الخط للتحكم في محاذاة الخط إلى محتوى طبقة PSD. |
| [getSize()](#getSize--) | يحصل أو يضبط عرض تأثير الخط. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | يحصل أو يضبط وضع المزج. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | يحصل أو يضبط إعدادات التعبئة. |
| [setOpacity(byte value)](#setOpacity-byte-) | يحصل أو يضبط الشفافية. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) سيخلط الخط مع محتويات الطبقة الحالية. |
| [setPosition(short value)](#setPosition-short-) | يحصل أو يضبط موضع تأثير الخط للتحكم في محاذاة الخط إلى محتوى طبقة PSD. |
| [setSize(int value)](#setSize-int-) | يحصل أو يضبط عرض تأثير الخط. |
| [setVisible(boolean value)](#setVisible-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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


يحصل على نوع التأثير

**Returns:**
int
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


يحصل أو يضبط إعدادات التعبئة.

القيمة: إعدادات التعبئة.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


يحصل أو يضبط الشفافية.

القيمة: الشفافية.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) سيخلط الخط مع محتويات الطبقة الحالية.

القيمة:  true  إذا كان يجب خلط الخط مع محتويات الطبقة الحالية؛ وإلا،  false .

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


يحصل أو يضبط موضع تأثير الخط للتحكم في محاذاة الخط إلى محتوى طبقة PSD. يمكن أن تكون القيمة [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) لرسم الخط داخل محتوى طبقة PSD، أو [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) لرسم الخط حول محتوى طبقة PSD، و[StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) لرسم الخط داخل وخارج.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


يحصل أو يضبط عرض تأثير الخط.

القيمة: عرض تأثير الخط.

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

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


يحصل أو يضبط إعدادات التعبئة.

القيمة: إعدادات التعبئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

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

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) سيخلط الخط مع محتويات الطبقة الحالية.

القيمة:  true  إذا كان يجب خلط الخط مع محتويات الطبقة الحالية؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


يحصل أو يضبط موضع تأثير الخط للتحكم في محاذاة الخط إلى محتوى طبقة PSD. يمكن أن تكون القيمة [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) لرسم الخط داخل محتوى طبقة PSD، أو [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) لرسم الخط حول محتوى طبقة PSD، و[StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) لرسم الخط داخل وخارج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


يحصل أو يضبط عرض تأثير الخط.

القيمة: عرض تأثير الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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

