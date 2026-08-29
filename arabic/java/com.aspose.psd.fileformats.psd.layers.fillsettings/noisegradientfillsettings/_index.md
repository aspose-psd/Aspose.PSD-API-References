---
title: "NoiseGradientFillSettings"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "فئة تعريف تدرج الضوضاء."
type: docs
weight: 18
url: /ar/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

فئة تعريف تدرج الضوضاء.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | ينشئ مثيلاً جديداً للفئة [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings). |
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
| [getColorModel()](#getColorModel--) | يحصل أو يعيّن نموذج اللون - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) مُبهّرًا. |
| [getExpansionCount()](#getExpansionCount--) | يحصل أو يعيّن عدد التوسيع ( = 2 لبرنامج Photoshop 6.0). |
| [getFillType()](#getFillType--) | نوع التعبئة. |
| [getGradientMode()](#getGradientMode--) | يحصل على الوضع لهذا التدرج. |
| [getGradientName()](#getGradientName--) | يحصل أو يعيّن اسم التدرج. |
| [getGradientType()](#getGradientType--) | يحصل أو يعيّن نوع التدرج. |
| [getHorizontalOffset()](#getHorizontalOffset--) | يحصل أو يعيّن الإزاحة الأفقية بالنسبة المئوية. |
| [getMaximumColor()](#getMaximumColor--) | يحصل أو يعيّن اللون الأقصى لـ PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | يحصل أو يعيّن اللون الأدنى لـ PixelDataFormat. |
| [getReverse()](#getReverse--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) مقلوبًا. |
| [getRndNumberSeed()](#getRndNumberSeed--) | يحصل أو يعيّن بذرة الرقم العشوائي المستخدمة لتوليد الألوان لتدرج الضوضاء Noise gradient |
| [getRoughness()](#getRoughness--) | يحصل أو يعيّن عامل الخشونة. |
| [getScale()](#getScale--) | يحصل أو يضبط المقياس. |
| [getShowTransparency()](#getShowTransparency--) | يحصل أو يعيّن العلامة لإظهار الشفافية. |
| [getUseVectorColor()](#getUseVectorColor--) | يحصل أو يعيّن العلامة لاستخدام اللون المتجه. |
| [getVerticalOffset()](#getVerticalOffset--) | يحصل أو يعيّن الإزاحة الرأسية بالنسبة المئوية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | يُثير تغيير القيمة. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | يحصل أو يعيّن الزاوية. |
| [setColorModel(short value)](#setColorModel-short-) | يحصل أو يعيّن نموذج اللون - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) مُبهّرًا. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | يحصل أو يعيّن عدد التوسيع ( = 2 لبرنامج Photoshop 6.0). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | يحصل على الوضع لهذا التدرج. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | يحصل أو يعيّن اسم التدرج. |
| [setGradientType(int value)](#setGradientType-int-) | يحصل أو يعيّن نوع التدرج. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | يحصل أو يعيّن الإزاحة الأفقية بالنسبة المئوية. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | يحصل أو يعيّن اللون الأقصى لـ PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | يحصل أو يعيّن اللون الأدنى لـ PixelDataFormat. |
| [setReverse(boolean value)](#setReverse-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) مقلوبًا. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | يحصل أو يعيّن بذرة الرقم العشوائي المستخدمة لتوليد الألوان لتدرج الضوضاء Noise gradient |
| [setRoughness(int value)](#setRoughness-int-) | يحصل أو يعيّن عامل الخشونة. |
| [setScale(int value)](#setScale-int-) | يحصل أو يضبط المقياس. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | يحصل أو يعيّن العلامة لإظهار الشفافية. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | يحصل أو يعيّن العلامة لاستخدام اللون المتجه. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | يحصل أو يعيّن الإزاحة الرأسية بالنسبة المئوية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


ينشئ مثيلاً جديداً للفئة [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings).

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


يحصل أو يعيّن نموذج اللون - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) مُبهّرًا.

القيمة: true إذا كان dither؛ وإلا false.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


يحصل أو يعيّن عدد التوسيع ( = 2 لبرنامج Photoshop 6.0).

**Returns:**
short
### getFillType() {#getFillType--}
```
public int getFillType()
```


نوع التعبئة.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


يحصل على الوضع لهذا التدرج. يحدد 'نوع التدرج' = 'صلب/ضوضاء' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


يحصل أو يعيّن اسم التدرج.

القيمة: اسم التدرج.

**Returns:**
java.lang.String
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


يحصل أو يعيّن اللون الأقصى لـ PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


يحصل أو يعيّن اللون الأدنى لـ PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) مقلوبًا.

القيمة: true إذا كان معكوسًا؛ وإلا false.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


يحصل أو يعيّن بذرة الرقم العشوائي المستخدمة لتوليد الألوان لتدرج الضوضاء Noise gradient

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


يحصل أو يعيّن عامل الخشونة.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


يحصل أو يضبط المقياس.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


يحصل أو يعيّن العلامة لإظهار الشفافية.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


يحصل أو يعيّن العلامة لاستخدام اللون المتجه.

**Returns:**
boolean
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


يحصل أو يعيّن نموذج اللون - RGB/HSB/LAB (3/4/6).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) مُبهّرًا.

القيمة: true إذا كان dither؛ وإلا false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


يحصل أو يعيّن عدد التوسيع ( = 2 لبرنامج Photoshop 6.0).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


يحصل على الوضع لهذا التدرج. يحدد 'نوع التدرج' = 'صلب/ضوضاء' (0/1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


يحصل أو يعيّن اسم التدرج.

القيمة: اسم التدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

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

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


يحصل أو يعيّن اللون الأقصى لـ PixelDataFormat.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


يحصل أو يعيّن اللون الأدنى لـ PixelDataFormat.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) مقلوبًا.

القيمة: true إذا كان معكوسًا؛ وإلا false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


يحصل أو يعيّن بذرة الرقم العشوائي المستخدمة لتوليد الألوان لتدرج الضوضاء Noise gradient

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


يحصل أو يعيّن عامل الخشونة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


يحصل أو يضبط المقياس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


يحصل أو يعيّن العلامة لإظهار الشفافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


يحصل أو يعيّن العلامة لاستخدام اللون المتجه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

