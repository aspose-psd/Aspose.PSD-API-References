---
title: "IGradientFillSettings"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الواجهة الأساسية لإعدادات تعبئة التدرج."
type: docs
weight: 23
url: /ar/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

الواجهة الأساسية لإعدادات تعبئة التدرج.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer]. |
| [getAngle()](#getAngle--) | يحصل أو يعيّن الزاوية. |
| [getDither()](#getDither--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) مُهزَّز. |
| [getGradient()](#getGradient--) | يحصل أو يعيّن مثيل تعريف التدرج المحدد (Solid/Noise). |
| [getGradientType()](#getGradientType--) | يحصل أو يعيّن نوع التدرج. |
| [getHorizontalOffset()](#getHorizontalOffset--) | يحصل أو يعيّن الإزاحة الأفقية. |
| [getInterpolationMethod()](#getInterpolationMethod--) | يحصل أو يعيّن طريقة الاستيفاء للتدرج. |
| [getReverse()](#getReverse--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) مقلوب. |
| [getScale()](#getScale--) | يحصل أو يعيّن مقياس التدرج  **normalized**  (بالنسبة المئوية). |
| [getVerticalOffset()](#getVerticalOffset--) | يحصل أو يعيّن الإزاحة العمودية. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | يحصل أو يعيّن الزاوية. |
| [setDither(boolean value)](#setDither-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) مُهزَّز. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | يحصل أو يعيّن مثيل تعريف التدرج المحدد (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | يحصل أو يعيّن نوع التدرج. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | يحصل أو يعيّن الإزاحة الأفقية. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | يحصل أو يعيّن طريقة الاستيفاء للتدرج. |
| [setReverse(boolean value)](#setReverse-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) مقلوب. |
| [setScale(int value)](#setScale-int-) | يحصل أو يعيّن مقياس التدرج  **normalized**  (بالنسبة المئوية). |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | يحصل أو يعيّن الإزاحة العمودية. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer].

القيمة:  true  إذا كان [align with layer]؛ وإلا،  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


يحصل أو يعيّن الزاوية.

القيمة: الزاوية.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) مُهزَّز.

القيمة: true إذا كان dither؛ وإلا false.

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


يحصل أو يعيّن مثيل تعريف التدرج المحدد (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


يحصل أو يعيّن نوع التدرج.

القيمة: نوع التدرج.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


يحصل أو يعيّن الإزاحة الأفقية.

القيمة: الإزاحة الأفقية.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


يحصل أو يعيّن طريقة الاستيفاء للتدرج.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) مقلوب.

القيمة: true إذا كان معكوسًا؛ وإلا false.

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


يحصل أو يعيّن مقياس التدرج  **normalized**  (بالنسبة المئوية).

القيمة: المقياس.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


يحصل أو يعيّن الإزاحة العمودية.

القيمة: الإزاحة العمودية.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer].

القيمة:  true  إذا كان [align with layer]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


يحصل أو يعيّن الزاوية.

القيمة: الزاوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) مُهزَّز.

القيمة: true إذا كان dither؛ وإلا false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


يحصل أو يعيّن مثيل تعريف التدرج المحدد (Solid/Noise).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


يحصل أو يعيّن نوع التدرج.

القيمة: نوع التدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


يحصل أو يعيّن الإزاحة الأفقية.

القيمة: الإزاحة الأفقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


يحصل أو يعيّن طريقة الاستيفاء للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) مقلوب.

القيمة: true إذا كان معكوسًا؛ وإلا false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


يحصل أو يعيّن مقياس التدرج  **normalized**  (بالنسبة المئوية).

القيمة: المقياس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


يحصل أو يعيّن الإزاحة العمودية.

القيمة: الإزاحة العمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

