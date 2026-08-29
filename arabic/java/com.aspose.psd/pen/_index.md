---
title: "Pen"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يعرّف كائنًا يُستخدم لرسم الخطوط والمنحنيات والأشكال."
type: docs
weight: 77
url: /ar/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

يعرّف كائنًا يُستخدم لرسم الخطوط والمنحنيات والأشكال.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | ينشئ مثيلًا جديدًا من الفئة Pen باللون المحدد. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | ينشئ مثيلًا جديدًا من الفئة Pen بالخصائص المحددة Color و Pen.Width. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | يُنشئ مثيلاً جديدًا من الفئة Pen باستخدام الـ Brush المحدد. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | يُنشئ مثيلاً جديدًا من الفئة Pen باستخدام الـ Brush المحدد و Pen.Width. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | يحصل على المحاذاة لهذا Pen. |
| [getBrush()](#getBrush--) | يحصل على الـ Brush الذي يحدد خصائص هذا Pen. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | يحصل على لون هذا Pen. |
| [getCompoundArray()](#getCompoundArray--) | يحصل على مصفوفة من القيم التي تحدد قلمًا مركبًا. |
| [getCustomEndCap()](#getCustomEndCap--) | يحصل على غطاء مخصص لاستخدامه في نهاية الخطوط المرسومة بهذا Pen. |
| [getCustomStartCap()](#getCustomStartCap--) | يحصل على غطاء مخصص لاستخدامه في بداية الخطوط المرسومة بهذا Pen. |
| [getDashCap()](#getDashCap--) | يحصل على نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا Pen. |
| [getDashOffset()](#getDashOffset--) | يحصل على المسافة من بداية الخط إلى بداية نمط الشرطة. |
| [getDashPattern()](#getDashPattern--) | يحصل على مصفوفة من الشرطات والمسافات المخصصة. |
| [getDashStyle()](#getDashStyle--) | يحصل على النمط المستخدم للخطوط المتقطعة المرسومة بهذا Pen. |
| [getEndCap()](#getEndCap--) | يحصل على نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا Pen. |
| [getLineJoin()](#getLineJoin--) | يحصل على نمط الوصلة لنهايات خطين متتاليين مرسومين بهذا Pen. |
| [getMiterLimit()](#getMiterLimit--) | يحصل على الحد الأقصى لسماكة الوصلة عند الزاوية المقطوعة. |
| [getOpacity()](#getOpacity--) | يحصل على شفافية الكائن. |
| [getPenType()](#getPenType--) | يحصل على نمط الخطوط المرسومة بهذا Pen. |
| [getStartCap()](#getStartCap--) | يحصل على نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا Pen. |
| [getTransform()](#getTransform--) | يحصل على نسخة من التحويل الهندسي لهذا Pen. |
| [getWidth()](#getWidth--) | يحصل على عرض هذا Pen، بوحدات كائن Graphics المستخدم في الرسم. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | يضرب مصفوفة التحويل لهذا Pen بالمصفوفة Matrix المحددة. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | يضرب مصفوفة التحويل لهذا Pen بالمصفوفة Matrix المحددة بالترتيب المحدد. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | يعيد تعيين مصفوفة التحويل الهندسي لهذا Pen إلى هوية. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يدور التحويل الهندسي المحلي بالزاوية المحددة. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يقوم بتغيير مقياس التحويل الهندسي المحلي بالعوامل المحددة. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يقوم بتكبير التحويل الهندسي المحلي بواسطة العوامل المحددة وفقًا للترتيب المحدد. |
| [setAlignment(int value)](#setAlignment-int-) | يضبط محاذاة هذا  Pen . |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | يضبط الـ  Brush  الذي يحدد خصائص هذا  Pen . |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | يضبط لون هذا  Pen . |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | يضبط مصفوفة القيم التي تحدد قلمًا مركبًا. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | يضبط غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا  Pen . |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا  Pen . |
| [setDashCap(int value)](#setDashCap-int-) | يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا  Pen . |
| [setDashOffset(float value)](#setDashOffset-float-) | يضبط المسافة من بداية الخط إلى بداية نمط الشرط. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | يضبط مصفوفة من الشرطات والمسافات المخصصة. |
| [setDashStyle(int value)](#setDashStyle-int-) | يضبط النمط المستخدم للخطوط المتقطعة المرسومة بهذا  Pen . |
| [setEndCap(int value)](#setEndCap-int-) | يضبط نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا  Pen . |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | يضبط القيم التي تحدد نمط الغطاء المستخدم لإنهاء الخطوط المرسومة بهذا  Pen . |
| [setLineJoin(int value)](#setLineJoin-int-) | يضبط نمط الوصلة لنهايات خطين متتاليين مرسومين بهذا  Pen . |
| [setMiterLimit(float value)](#setMiterLimit-float-) | يضبط حد سمك الوصلة عند الزاوية المشطوفة. |
| [setOpacity(float value)](#setOpacity-float-) | يضبط شفافية الكائن. |
| [setStartCap(int value)](#setStartCap-int-) | يضبط نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا  Pen . |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | يضبط نسخة من التحويل الهندسي لهذا  Pen . |
| [setWidth(float value)](#setWidth-float-) | يضبط عرض هذا  Pen ، بوحدات كائن الـ Graphics المستخدم للرسم. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


ينشئ مثيلًا جديدًا من الفئة Pen باللون المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | هيكل  Color  يوضح لون هذا  Pen . |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


ينشئ مثيلًا جديدًا من الفئة Pen بالخصائص المحددة Color و Pen.Width.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | هيكل  Color  يوضح لون هذا  Pen . |
| العرض | float | قيمة تشير إلى عرض هذا  Pen . |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


يُنشئ مثيلاً جديدًا من الفئة Pen باستخدام الـ Brush المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | ـ Brush  يحدد خصائص التعبئة لهذا  Pen . |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


يُنشئ مثيلاً جديدًا من الفئة Pen باستخدام الـ Brush المحدد و Pen.Width.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | ـ Brush  يحدد خصائص هذا  Pen . |
| العرض | float | عرض القلم الجديد  Pen . |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


يحصل على المحاذاة لهذا Pen.

**Returns:**
int - PenAlignment التي تمثل المحاذاة لهذا Pen.
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


يحصل على الـ Brush الذي يحدد خصائص هذا Pen.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


يحصل على لون هذا Pen.

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


يحصل على مصفوفة من القيم التي تحدد قلمًا مركبًا. القلم المركب يرسم خطًا مركبًا مكوّنًا من خطوط متوازية ومسافات.

**Returns:**
float[] - مصفوفة من الأعداد الحقيقية التي تحدد المصفوفة المركبة. يجب أن تكون العناصر في المصفوفة بترتيب تصاعدي، لا تقل عن 0، ولا تزيد عن 1.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


يحصل على غطاء مخصص لاستخدامه في نهاية الخطوط المرسومة بهذا Pen.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


يحصل على غطاء مخصص لاستخدامه في بداية الخطوط المرسومة بهذا Pen.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


يحصل على نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا Pen.

**Returns:**
int - أحد قيم DashCap التي تمثل نمط الغطاء المستخدم في بداية ونهاية الشرط التي تشكل الخطوط المتقطعة المرسومة بهذا Pen.
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


يحصل على المسافة من بداية الخط إلى بداية نمط الشرطة.

**Returns:**
float - المسافة من بداية الخط إلى بداية نمط الشرط.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


يحصل على مصفوفة من الشرطات والمسافات المخصصة.

**Returns:**
float[] - مصفوفة من الأعداد الحقيقية التي تحدد أطوال الشرط المتناوبة والمسافات في الخطوط المتقطعة.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


يحصل على النمط المستخدم للخطوط المتقطعة المرسومة بهذا Pen.

**Returns:**
int - DashStyle التي تمثل النمط المستخدم للخطوط المتقطعة المرسومة بهذا Pen.
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


يحصل على نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا Pen.

**Returns:**
int - أحد قيم LineCap التي تمثل نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا Pen.
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


يحصل على نمط الوصلة لنهايات خطين متتاليين مرسومين بهذا Pen.

**Returns:**
int - LineJoin التي تمثل نمط الوصل لنهايات خطين متتاليين مرسومين بهذا Pen.
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


يحصل على الحد الأقصى لسماكة الوصلة عند الزاوية المقطوعة.

**Returns:**
float - الحد الأقصى لسماكة الوصل عند زاوية ميتة.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


يحصل على شفافية الكائن. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الكائن مرئي بالكامل، والقيمة 1 تعني أن الكائن معتم بالكامل.

**Returns:**
float - قيمة الشفافية.
### getPenType() {#getPenType--}
```
public int getPenType()
```


يحصل على نمط الخطوط المرسومة بهذا Pen.

**Returns:**
int - تعداد PenType الذي يحدد نمط الخطوط المرسومة بهذا Pen.
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


يحصل على نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا Pen.

**Returns:**
int - أحد قيم LineCap التي تمثل نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا Pen.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


يحصل على نسخة من التحويل الهندسي لهذا Pen.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


يحصل على عرض هذا Pen، بوحدات كائن Graphics المستخدم في الرسم.

**Returns:**
float - عرض هذا Pen.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


يضرب مصفوفة التحويل لهذا Pen بالمصفوفة Matrix المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | كائن Matrix الذي يُستخدم لضرب مصفوفة التحويل. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


يضرب مصفوفة التحويل لهذا Pen بالمصفوفة Matrix المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrix الذي يُستخدم لضرب مصفوفة التحويل. |
| الترتيب | int | الترتيب الذي يتم فيه تنفيذ عملية الضرب. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


يعيد تعيين مصفوفة التحويل الهندسي لهذا Pen إلى هوية.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


يدور التحويل الهندسي المحلي بالزاوية المحددة. هذه الطريقة تُضيف الدوران إلى التحويل في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |
| الترتيب | int | MatrixOrder التي تحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة الدوران. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة. هذه الطريقة تُضيف مصفوفة التحجيم إلى التحويل في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور x. |
| sy | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


يقوم بتكبير التحويل الهندسي المحلي بواسطة العوامل المحددة وفقًا للترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور x. |
| sy | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور y. |
| الترتيب | int | MatrixOrder التي تحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة التحجيم. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


يضبط محاذاة هذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | PenAlignment التي تمثل المحاذاة لهذا Pen. |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


يضبط الـ  Brush  الذي يحدد خصائص هذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | Brush التي تحدد خصائص هذا Pen. |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


يضبط لون هذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Color التي تمثل لون هذا Pen. |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


يضبط مصفوفة من القيم التي تحدد قلمًا مركبًا. القلم المركب يرسم خطًا مركبًا مكوّنًا من خطوط متوازية ومسافات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float[] | مصفوفة من الأعداد الحقيقية التي تحدد المصفوفة المركبة. يجب أن تكون عناصر المصفوفة بترتيب تصاعدي، لا تقل عن 0 ولا تزيد عن 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


يضبط غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | CustomLineCap التي تمثل الغطاء المستخدم في نهاية الخطوط المرسومة بهذه Pen. |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | CustomLineCap التي تمثل الغطاء المستخدم في بداية الخطوط المرسومة بهذه Pen. |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | إحدى قيم DashCap التي تمثل نمط الغطاء المستخدم في بداية ونهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذه Pen. |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


يضبط المسافة من بداية الخط إلى بداية نمط الشرط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | المسافة من بداية الخط إلى بداية نمط الشرطة. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


يضبط مصفوفة من الشرطات والمسافات المخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float[] | مصفوفة من الأعداد الحقيقية التي تحدد أطوال الشرطات والمسافات المتناوبة في الخطوط المتقطعة. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


يضبط النمط المستخدم للخطوط المتقطعة المرسومة بهذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | DashStyle التي تمثل النمط المستخدم للخطوط المتقطعة المرسومة بهذه Pen. |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


يضبط نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | إحدى قيم LineCap التي تمثل نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذه Pen. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


يضبط القيم التي تحدد نمط الغطاء المستخدم لإنهاء الخطوط المرسومة بهذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startCap | int | LineCap التي تمثل نمط الغطاء لاستخدامه في بداية الخطوط المرسومة بهذه Pen. |
| endCap | int | LineCap التي تمثل نمط الغطاء لاستخدامه في نهاية الخطوط المرسومة بهذه Pen. |
| dashCap | int | LineCap التي تمثل نمط الغطاء لاستخدامه في بداية أو نهاية الخطوط المتقطعة المرسومة بهذه Pen. |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


يضبط نمط الوصلة لنهايات خطين متتاليين مرسومين بهذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | LineJoin التي تمثل نمط الوصل لنهايات خطين متتاليين مرسومين بهذه Pen. |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


يضبط حد سمك الوصلة عند الزاوية المشطوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | حد سمك الوصل عند زاوية ميتة. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


يضبط شفافية الكائن. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الكائن مرئي بالكامل، والقيمة 1 تعني أن الكائن معتم بالكامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | قيمة الشفافية. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


يضبط نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | إحدى قيم LineCap التي تمثل نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذه Pen. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


يضبط نسخة من التحويل الهندسي لهذا  Pen .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | نسخة من Matrix التي تمثل التحويل الهندسي لهذا Pen. |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


يضبط عرض هذا  Pen ، بوحدات كائن الـ Graphics المستخدم للرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | عرض هذا Pen. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |
| الترتيب | int | الترتيب (سابق أو لاحق) لتطبيق الترجمة. |

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

