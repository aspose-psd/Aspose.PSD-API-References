---
title: "MotionWienerFilterOptions"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "خيارات مرشح فك الالتفاف     إزالة تشويش الحركة"
type: docs
weight: 18
url: /ar/java/com.aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends DeconvolutionFilterOptions
```

خيارات مرشح فك الالتفاف لإزالة الضبابية الحركة
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MotionWienerFilterOptions(int length, double smooth, double angle)](#MotionWienerFilterOptions-int-double-double-) | ينشئ مثيلاً جديداً من الفئة  MotionWienerFilterOptions  . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | يحصل أو يعيّن الزاوية بالدرجات. |
| [getBrightness()](#getBrightness--) | يحصل أو يضبط السطوع. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) بتدرج رمادي. |
| [getLength()](#getLength--) | يحصل أو يعيّن الطول. |
| [getSmooth()](#getSmooth--) | يحصل أو يعيّن السلاسة. |
| [getSnr()](#getSnr--) | يحصل أو يعيّن نسبة الإشارة إلى الضوضاء (SNR) النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل محملاً جزئياً. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(double value)](#setAngle-double-) | يحصل أو يعيّن الزاوية بالدرجات. |
| [setBrightness(double value)](#setBrightness-double-) | يحصل أو يضبط السطوع. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) بتدرج رمادي. |
| [setLength(int value)](#setLength-int-) | يحصل أو يعيّن الطول. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل محملاً جزئياً. |
| [setSmooth(double value)](#setSmooth-double-) | يحصل أو يعيّن السلاسة. |
| [setSnr(double value)](#setSnr-double-) | يحصل أو يعيّن نسبة الإشارة إلى الضوضاء (SNR) النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MotionWienerFilterOptions(int length, double smooth, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int length, double smooth, double angle)
```


ينشئ مثيلاً جديداً من الفئة  MotionWienerFilterOptions  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| length | int | الطول. |
| سلاسة | double | السلاسة. |
| زاوية | double | الزاوية بالدرجات. |

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
public double getAngle()
```


يحصل أو يعيّن الزاوية بالدرجات.

القيمة: الزاوية.

**Returns:**
double
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


يحصل أو يعيّن السطوع. النطاق الموصى به 1 - 1.5 القيمة الافتراضية = 1.15

القيمة: السطوع.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) بتدرج رمادي. إرجاع وضع التدرج الرمادي أو وضع RGB.

القيمة:  true  إذا كان بتدرج رمادي؛ وإلا،  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


يحصل أو يعيّن الطول.

القيمة: الطول.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


يحصل أو يعيّن السلاسة.

القيمة: السلاسة.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


يحصل أو يعيّن نسبة الإشارة إلى الضوضاء (SNR) النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007

القيمة: نسبة الإشارة إلى الضوضاء.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


يحصل على قيمة تشير إلى ما إذا كان هذا المثيل محملاً جزئياً.

القيمة:  true  إذا تم تحميل هذا الكائن جزئياً؛ وإلا،  false .

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




### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```


يحصل أو يعيّن الزاوية بالدرجات.

القيمة: الزاوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


يحصل أو يعيّن السطوع. النطاق الموصى به 1 - 1.5 القيمة الافتراضية = 1.15

القيمة: السطوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) بتدرج رمادي. إرجاع وضع التدرج الرمادي أو وضع RGB.

القيمة:  true  إذا كان بتدرج رمادي؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


يحصل أو يعيّن الطول.

القيمة: الطول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


يحصل على قيمة تشير إلى ما إذا كان هذا المثيل محملاً جزئياً.

القيمة:  true  إذا تم تحميل هذا الكائن جزئياً؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


يحصل أو يعيّن السلاسة.

القيمة: السلاسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


يحصل أو يعيّن نسبة الإشارة إلى الضوضاء (SNR) النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007

القيمة: نسبة الإشارة إلى الضوضاء.

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

