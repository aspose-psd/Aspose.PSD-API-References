---
title: "OuterGlowEffect"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تأثير طبقة التوهج الخارجي"
type: docs
weight: 15
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

تأثير طبقة التوهج الخارجي
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
| [getFillColor()](#getFillColor--) | يحصل أو يعيّن اللون. |
| [getIntensity()](#getIntensity--) | يحصل أو يعيّن الزاوية بالدرجات. |
| [getJitter()](#getJitter--) | يحصل أو يعيّن الضوضاء. |
| [getNoise()](#getNoise--) | يحصل أو يعيّن الضوضاء. |
| [getOpacity()](#getOpacity--) | يحصل أو يضبط الشفافية. |
| [getRange()](#getRange--) | يحصل أو يعيّن الضوضاء. |
| [getSize()](#getSize--) | يحصل على قيمة الضبابية بالبكسل. |
| [getSpread()](#getSpread--) | يحصل أو يعيّن الشدة كنسبة مئوية. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | يحصل أو يضبط تأثير AntiAliasing الممكّن. |
| [isSoftBlend()](#isSoftBlend--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [knocks out]. |
| [isVisible()](#isVisible--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | يحصل أو يضبط تأثير AntiAliasing الممكّن. |
| [setBlendMode(long value)](#setBlendMode-long-) | يحصل أو يضبط وضع المزج. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | يحصل أو يعيّن اللون. |
| [setIntensity(int value)](#setIntensity-int-) | يحصل أو يعيّن الزاوية بالدرجات. |
| [setJitter(int value)](#setJitter-int-) | يحصل أو يعيّن الضوضاء. |
| [setNoise(int value)](#setNoise-int-) | يحصل أو يعيّن الضوضاء. |
| [setOpacity(byte value)](#setOpacity-byte-) | يحصل أو يضبط الشفافية. |
| [setRange(int value)](#setRange-int-) | يحصل أو يعيّن الضوضاء. |
| [setSize(int value)](#setSize-int-) | يحصل على قيمة الضبابية بالبكسل. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | يحصل أو يعيّن الشدة كنسبة مئوية. |
| [setVisible(boolean value)](#setVisible-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


يحصل أو يعيّن اللون.

القيمة: اللون.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


يحصل أو يعيّن الزاوية بالدرجات.

القيمة: الزاوية.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


يحصل أو يعيّن الضوضاء.

**Returns:**
int
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
### getRange() {#getRange--}
```
public final int getRange()
```


يحصل أو يعيّن الضوضاء.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


يحصل على قيمة الضبابية بالبكسل.

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


يحصل أو يضبط تأثير AntiAliasing الممكّن.

القيمة: المسافة.

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [knocks out].

القيمة:  true  إذا كان [knocks out]; وإلا،  false .

**Returns:**
boolean
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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


يحصل أو يضبط تأثير AntiAliasing الممكّن.

القيمة: المسافة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


يحصل أو يعيّن اللون.

القيمة: اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


يحصل أو يعيّن الزاوية بالدرجات.

القيمة: الزاوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


يحصل أو يعيّن الضوضاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


يحصل أو يعيّن الضوضاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


يحصل على قيمة الضبابية بالبكسل.

القيمة: الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [knocks out].

القيمة:  true  إذا كان [knocks out]; وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

