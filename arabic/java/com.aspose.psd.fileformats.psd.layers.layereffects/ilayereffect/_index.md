---
title: "ILayerEffect"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "واجهة لتأثيرات الطبقة"
type: docs
weight: 20
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

واجهة لتأثيرات الطبقة
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | يحصل أو يضبط وضع المزج. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | احسب واحصل على حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة. |
| [getEffectType()](#getEffectType--) | يحصل على نوع التأثير |
| [getOpacity()](#getOpacity--) | يحصل أو يضبط الشفافية حيث 255 = 100% |
| [isVisible()](#isVisible--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
| [setBlendMode(long value)](#setBlendMode-long-) | يحصل أو يضبط وضع المزج. |
| [setOpacity(byte value)](#setOpacity-byte-) | يحصل أو يضبط الشفافية حيث 255 = 100% |
| [setVisible(boolean value)](#setVisible-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


يحصل أو يضبط وضع المزج.

القيمة: وضع المزج.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


احسب واحصل على حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود بكسلات الطبقة. |
| globalAngle | int | الزاوية العامة لحساب زاوية الضوء العامة. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


يحصل على نوع التأثير

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


يحصل أو يضبط الشفافية حيث 255 = 100%

القيمة: الشفافية.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية.

القيمة:  true  إذا كان هذا الكائن مرئيًا؛ وإلا،  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


يحصل أو يضبط وضع المزج.

القيمة: وضع المزج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


يحصل أو يضبط الشفافية حيث 255 = 100%

القيمة: الشفافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه النسخة مرئية.

القيمة:  true  إذا كان هذا الكائن مرئيًا؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

