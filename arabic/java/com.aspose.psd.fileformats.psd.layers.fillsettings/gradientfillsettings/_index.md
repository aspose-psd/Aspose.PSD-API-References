---
title: "GradientFillSettings"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "إعدادات تأثير تعبئة التدرج."
type: docs
weight: 14
url: /ar/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

إعدادات تأثير تعبئة التدرج.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | يُهيئ مثيلاً جديدًا للفئة [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer]. |
| [getAngle()](#getAngle--) | يحصل أو يعيّن الزاوية. |
| [getClass()](#getClass--) |  |
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | يحصل أو يعيّن حدود حاوية الطبقة لحساب موضع التدرج بشكل صحيح. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | يحسب ويعيد مقياس التدرج **denormalized** (مقياس واجهة المستخدم) المقابل للقيمة الحالية للـ Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [getDither()](#getDither--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) يستخدم الـ dither. |
| [getFillType()](#getFillType--) | نوع التعبئة. |
| [getGradient()](#getGradient--) | يحصل أو يعيّن مثيل تعريف التدرج المحدد (Solid/Noise). |
| [getGradientType()](#getGradientType--) | يحصل أو يعيّن نوع التدرج. |
| [getHorizontalOffset()](#getHorizontalOffset--) | يحصل أو يعيّن الإزاحة الأفقية بالنسبة المئوية. |
| [getInterpolationMethod()](#getInterpolationMethod--) | يحصل أو يعيّن طريقة الاستيفاء للتدرج. |
| [getReverse()](#getReverse--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) معكوسًا. |
| [getScale()](#getScale--) | يحصل أو يعيّن مقياس التدرج **normalized** (بالنسبة المئوية) |
| [getVerticalOffset()](#getVerticalOffset--) | يحصل أو يعيّن الإزاحة الرأسية بالنسبة المئوية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | يُثير تغيير القيمة. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | يحصل أو يعيّن الزاوية. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | يحصل أو يعيّن حدود حاوية الطبقة لحساب موضع التدرج بشكل صحيح. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | يحوّل قيمة مقياس denormalized (UI) المحددة إلى ما يعادلها **normalized** ويعيّنها إلى Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) يستخدم الـ dither. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | يحصل أو يعيّن مثيل تعريف التدرج المحدد (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | يحصل أو يعيّن نوع التدرج. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | يحصل أو يعيّن الإزاحة الأفقية بالنسبة المئوية. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | يحصل أو يعيّن طريقة الاستيفاء للتدرج. |
| [setReverse(boolean value)](#setReverse-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) معكوسًا. |
| [setScale(int value)](#setScale-int-) | يحصل أو يعيّن مقياس التدرج **normalized** (بالنسبة المئوية) |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | يحصل أو يعيّن الإزاحة الرأسية بالنسبة المئوية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


يُهيئ مثيلاً جديدًا للفئة [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer].

القيمة:  true  إذا كان [align with layer]؛ وإلا،  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


يحصل أو يعيّن الزاوية.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


يحصل أو يعيّن حدود حاوية الطبقة لحساب موضع التدرج بشكل صحيح.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


يحسب ويعيد مقياس التدرج **denormalized** (مقياس واجهة المستخدم) المقابل للقيمة الحالية للـ Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | حدود التدرج. |

**Returns:**
int - المقياس غير المعياري (UI) بالنسبة المئوية كما يتم عرضه في Photoshop.
### getDither() {#getDither--}
```
public final boolean getDither()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) يستخدم الـ dither.

القيمة: true إذا كان dither؛ وإلا false.

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


نوع التعبئة.

**Returns:**
int
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


يحصل أو يعيّن مثيل تعريف التدرج المحدد (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


يحصل أو يعيّن نوع التدرج.

القيمة: نوع التدرج.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


يحصل أو يعيّن الإزاحة الأفقية بالنسبة المئوية.

القيمة: الإزاحة الأفقية.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


يحصل أو يعيّن طريقة الاستيفاء للتدرج.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) معكوسًا.

القيمة: true إذا كان معكوسًا؛ وإلا false.

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


يحصل أو يعيّن مقياس التدرج **normalized** (بالنسبة المئوية)

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


يحصل أو يعيّن الإزاحة الرأسية بالنسبة المئوية.

القيمة: الإزاحة العمودية.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


يُثير تغيير القيمة.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer].

القيمة:  true  إذا كان [align with layer]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


يحصل أو يعيّن الزاوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


يحصل أو يعيّن حدود حاوية الطبقة لحساب موضع التدرج بشكل صحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


يقوم بتحويل قيمة المقياس غير المعياري (UI) المحددة إلى ما يعادلها **normalized** ويعينها إلى Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). يطبق التحويل زاوية الـ gradient\\u2019s الحالية ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) والمساحة المملوءة fillArea لحساب عامل التطبيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | المقياس غير المعياري، مقياس UI بالنسبة المئوية كما يتم عرضه في Photoshop؛ |
| fillArea | [Size](../../com.aspose.psd/size) | حدود التدرج. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) يستخدم الـ dither.

القيمة: true إذا كان dither؛ وإلا false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


يحصل أو يعيّن مثيل تعريف التدرج المحدد (Solid/Noise).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


يحصل أو يعيّن نوع التدرج.

القيمة: نوع التدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


يحصل أو يعيّن الإزاحة الأفقية بالنسبة المئوية.

القيمة: الإزاحة الأفقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


يحصل أو يعيّن طريقة الاستيفاء للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) معكوسًا.

القيمة: true إذا كان معكوسًا؛ وإلا false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


يحصل أو يعيّن مقياس التدرج **normalized** (بالنسبة المئوية)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


يحصل أو يعيّن الإزاحة الرأسية بالنسبة المئوية.

القيمة: الإزاحة العمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

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

