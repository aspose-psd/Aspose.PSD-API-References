---
title: "TiffRational"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "نوع TIFF النسبي."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

نوع TIFF النسبي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffRational()](#TiffRational--) | ينشئ مثيلاً جديداً للفئة  TiffRational  . |
| [TiffRational(long value)](#TiffRational-long-) | ينشئ مثيلاً جديداً للفئة  TiffRational  . |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | ينشئ مثيلاً جديداً للفئة  TiffRational  . |
## الحقول

| حقل | الوصف |
| --- | --- |
| [Epsilon](#Epsilon) | الإبسيلون لحساب الكسر |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | يقرب القيمة المقدمة إلى كسر. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | يقرب القيمة المقدمة إلى كسر. |
| [approximateFraction(float value)](#approximateFraction-float-) | يقرب القيمة المقدمة إلى كسر. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | يقرب القيمة المقدمة إلى كسر. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد مساويًا لهذا المثيل. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | يحصل على المقام. |
| [getNominator()](#getNominator--) | يحصل على البسط. |
| [getValue()](#getValue--) | يحصل على القيمة العائمة. |
| [getValueD()](#getValueD--) | يحصل على القيمة المزدوجة. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يرجع  System.String  الذي يمثل هذه الحالة. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


ينشئ مثيلاً جديداً للفئة  TiffRational  .

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


ينشئ مثيلاً جديداً للفئة  TiffRational  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | long | قيمة البسط. |

سيتم استخدام البسط كالقيمة المحددة وسيكون المقام مساويًا لـ 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


ينشئ مثيلاً جديداً للفئة  TiffRational  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البسط | long | البسط. |
| المقام | long | المقام. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


الإبسيلون لحساب الكسر

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة. |
| إبسيلون | double | الخطأ المسموح به. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة. |
| إبسيلون | double | الخطأ المسموح به. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد مساويًا لهذا المثيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع هذه الحالة. |

**Returns:**
منطقي -  true  إذا كان الكائن المحدد مساويًا لهذه الحالة؛ وإلا،  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


يحصل على المقام.

القيمة: المقام.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


يحصل على البسط.

القيمة: البسط.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


يحصل على القيمة العائمة.

القيمة: قيمة float.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


يحصل على القيمة المزدوجة.

القيمة: القيمة العشرية.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذا الكائن.

**Returns:**
int - رمز تجزئة لهذا الكائن، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


يرجع  System.String  الذي يمثل هذه الحالة.

**Returns:**
java.lang.String - سلسلة System.String تمثل هذه الحالة.
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

