---
title: "RawColor"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تساعد فئة Raw Color Class على تخزين الألوان بأي عدد قنوات وأي وضع لون وأي عمق بت. يرجى ملاحظة أن بعض الفئات الداخلية قد تواجه مشكلات في تحويل RawColor إلى تنسيقها الأصلي، لذا إذا قدمت لك الواجهة البرمجية لون CMYK، فمن الأكثر موثوقية استخدام التنسيق المقدم."
type: docs
weight: 11
url: /ar/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

تساعد فئة Raw Color Class على تخزين الألوان بأي عدد قنوات، وأي وضع لون، وأي عمق بت. يرجى ملاحظة أن بعض الفئات الداخلية قد تواجه مشكلات في تحويل RawColor إلى تنسيقها الأصلي، لذا إذا قدمت لك الواجهة البرمجية لون CMYK، فمن الأكثر موثوقية استخدام التنسيق المقدم. أيضًا، قد تكون هناك بعض الحالات التي يمكن فيها تحويل Raw Color.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | يُنشئ نسخة جديدة من الفئة [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor). |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | يُنشئ نسخة جديدة من الفئة [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) من تنسيق بيانات البكسل باستخدام أوضاع اللون المحددة مسبقًا. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد يساوي هذه النسخة. |
| [getAsInt()](#getAsInt--) | يحصل على اللون كعدد صحيح (int) إذا كان ذلك ممكنًا. |
| [getAsLong()](#getAsLong--) | يحصل على اللون كعدد طويل (long) إذا كان ذلك ممكنًا. |
| [getBitDepth()](#getBitDepth--) | يحصل على عمق البت للون Raw Color. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | الوضع الذي سيتبعه اللون. |
| [getColorModeName()](#getColorModeName--) | يحصل على اسم وضع اللون. |
| [getComponents()](#getComponents--) | يحصل على مكونات اللون. |
| [hashCode()](#hashCode--) | احصل على قيمة التجزئة (hash code) للكائن الحالي. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | ينفّذ العامل ==. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | ينفّذ العامل !=. |
| [setAsInt(int value)](#setAsInt-int-) | يضبط البيانات لجميع القنوات من الوسيط من نوع int إذا كان ذلك ممكنًا. |
| [setAsLong(long value)](#setAsLong-long-) | يضبط البيانات لجميع القنوات من الوسيط من نوع int إذا كان ذلك ممكنًا. |
| [setColorMode(short value)](#setColorMode-short-) | الوضع الذي سيتبعه اللون. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


يُنشئ نسخة جديدة من الفئة [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | مكونات اللون المخصصة. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


يُنشئ نسخة جديدة من الفئة [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) من تنسيق بيانات البكسل باستخدام أوضاع اللون المحددة مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | تنسيق بيانات البكسل. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد يساوي هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع هذه الحالة. |

**Returns:**
منطقي -  true  إذا كان الكائن المحدد مساويًا لهذه الحالة؛ وإلا،  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


يحصل على اللون كعدد صحيح (int) إذا كان ذلك ممكنًا.

**Returns:**
int - بيانات القنوات المخزنة كـ Int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


يحصل على اللون كعدد طويل (long) إذا كان ذلك ممكنًا.

**Returns:**
long - بيانات القنوات المخزنة في Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


يحصل على عمق البت للون Raw Color. على سبيل المثال، للون ARGB مع 8 بت لكل قناة/مكوّن يكون عمق البت 32. عمق البت للون ARGB الكامل مع 16 بت لكل قناة/مكوّن يكون 64. يتم تجميع عمق البت من مجموع أعماق البت للقنوات. هذا ممكن إذا كانت القنوات المختلفة لها أعماق بت مختلفة.

**Returns:**
int - مجموع أعماق البت لجميع القنوات
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


الوضع الذي سيتبعه اللون.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


يحصل على اسم وضع اللون. يتم تجميع اسم وضع اللون من أسماء القنوات/المكونات.

**Returns:**
java.lang.String - سلسلة مع اسم وضع اللون
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


يحصل على مكونات اللون. كل مكوّن هو قناة منفصلة، وإذا كنت تستخدم نظام ألوان غير شائع، فمن الأفضل العمل مع كل قناة على حدة.

القيمة: مكونات اللون

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


احصل على قيمة التجزئة (hash code) للكائن الحالي.

**Returns:**
int - رمز التجزئة.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


ينفّذ العامل ==.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | الـ RawColor الأول. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | الـ RawColor الثاني. |

**Returns:**
boolean - نتيجة العملية.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


ينفّذ العامل !=.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | الـ RawColor الأول. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | الـ RawColor الثاني. |

**Returns:**
boolean - نتيجة العملية.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


يضبط البيانات لجميع القنوات من الوسيط من نوع int إذا كان ذلك ممكنًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة int التي تحتوي على بيانات المكوّن |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


يضبط البيانات لجميع القنوات من الوسيط من نوع int إذا كان ذلك ممكنًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long | القيمة int التي تحتوي على بيانات المكوّن |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


الوضع الذي سيتبعه اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

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

