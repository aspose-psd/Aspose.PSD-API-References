---
title: "DropShadowEffect"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تأثير طبقة الظل المتساقط"
type: docs
weight: 12
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class DropShadowEffect implements IShadowEffect, IInternalLayerEffect
```

تأثير طبقة الظل المتساقط
## الطرق

| طريقة | الوصف |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | يحصل أو يعيّن الزاوية بالدرجات. |
| [getBlendMode()](#getBlendMode--) | يحصل أو يضبط وضع المزج. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | يحصل أو يعيّن اللون. |
| [getDistance()](#getDistance--) | يحصل أو يعيّن المسافة بالبكسل. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | احسب واحصل على حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | يحصل على الكيان |
| [getEffectType()](#getEffectType--) | يحصل على نوع التأثير |
| [getKnocksOut()](#getKnocksOut--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [knocks out]. |
| [getNoise()](#getNoise--) | يحصل أو يعيّن الضوضاء. |
| [getOpacity()](#getOpacity--) | يحصل أو يضبط الشفافية. |
| [getSize()](#getSize--) | يحصل أو يعيّن قيمة الضبابية بالبكسل. |
| [getSpread()](#getSpread--) | يحصل أو يعيّن الشدة كنسبة مئوية. |
| [getUseGlobalLight()](#getUseGlobalLight--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [use this angle in all of the layer effects]. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | يحصل أو يعيّن الزاوية بالدرجات. |
| [setBlendMode(long value)](#setBlendMode-long-) | يحصل أو يضبط وضع المزج. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | يحصل أو يعيّن اللون. |
| [setDistance(int value)](#setDistance-int-) | يحصل أو يعيّن المسافة بالبكسل. |
| [setKnocksOut(boolean value)](#setKnocksOut-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [knocks out]. |
| [setNoise(int value)](#setNoise-int-) | يحصل أو يعيّن الضوضاء. |
| [setOpacity(byte value)](#setOpacity-byte-) | يحصل أو يضبط الشفافية. |
| [setSize(int value)](#setSize-int-) | يحصل أو يعيّن قيمة الضبابية بالبكسل. |
| [setSpread(int value)](#setSpread-int-) | يحصل أو يعيّن الشدة كنسبة مئوية. |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [use this angle in all of the layer effects]. |
| [setVisible(boolean value)](#setVisible-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static DropShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect)
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
### getAngle() {#getAngle--}
```
public final int getAngle()
```


يحصل أو يعيّن الزاوية بالدرجات.

القيمة: الزاوية.

**Returns:**
int
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
### getColor() {#getColor--}
```
public final Color getColor()
```


يحصل أو يعيّن اللون.

القيمة: اللون.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public final int getDistance()
```


يحصل أو يعيّن المسافة بالبكسل.

القيمة: المسافة.

**Returns:**
int
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
### getKnocksOut() {#getKnocksOut--}
```
public final boolean getKnocksOut()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [knocks out].

القيمة:  true  إذا كان [knocks out]; وإلا،  false .

**Returns:**
boolean
### getNoise() {#getNoise--}
```
public final int getNoise()
```


يحصل أو يعيّن الضوضاء.

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
### getSize() {#getSize--}
```
public final int getSize()
```


يحصل أو يعيّن قيمة الضبابية بالبكسل.

القيمة: الحجم.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


يحصل أو يعيّن الشدة كنسبة مئوية.

القيمة: الانتشار.

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [use this angle in all of the layer effects].

القيمة: true إذا كان [use global light]؛ وإلا false.

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




### setAngle(int value) {#setAngle-int-}
```
public final void setAngle(int value)
```


يحصل أو يعيّن الزاوية بالدرجات.

القيمة: الزاوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


يحصل أو يعيّن اللون.

القيمة: اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


يحصل أو يعيّن المسافة بالبكسل.

القيمة: المسافة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setKnocksOut(boolean value) {#setKnocksOut-boolean-}
```
public final void setKnocksOut(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [knocks out].

القيمة:  true  إذا كان [knocks out]; وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


يحصل أو يعيّن الضوضاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


يحصل أو يعيّن قيمة الضبابية بالبكسل.

القيمة: الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


يحصل أو يعيّن الشدة كنسبة مئوية.

القيمة: الانتشار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [use this angle in all of the layer effects].

القيمة: true إذا كان [use global light]؛ وإلا false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

