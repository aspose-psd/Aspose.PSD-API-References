---
title: "StringFormat"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يغلف معلومات تخطيط النص مثل المحاذاة والاتجاه وإيقافات الجدولة، وتعديلات العرض مثل إدراج الحذف الثلاثي واستبدال الأرقام الوطنية وميزات OpenType."
type: docs
weight: 106
url: /ar/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

يغلف معلومات تخطيط النص (مثل المحاذاة والاتجاه وإيقافات الجدولة) وتعديلات العرض (مثل إدراج الحذف الثلاثي واستبدال الأرقام الوطنية) وميزات OpenType. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [StringFormat()](#StringFormat--) | يُنشئ كائنًا جديدًا من  com.aspose.psd.StringFormat . |
| [StringFormat(int options)](#StringFormat-int-) | يُنشئ كائنًا جديدًا من  com.aspose.psd.StringFormat  مع تعداد  com.aspose.psd.StringFormatFlags  المحدد واللغة. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | يُنشئ كائنًا جديدًا من  com.aspose.psd.StringFormat  استنادًا إلى كائن  com.aspose.psd.StringFormat  الموجود المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذا الكائن  com.aspose.psd.StringFormat . |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | يحصل على معلومات محاذاة النص في المستوى الرأسي. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | يحصل على اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | يحصل على الطريقة المستخدمة لاستبدال الأرقام. |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getFirstTabOffset()](#getFirstTabOffset--) | يحصل على عدد المسافات بين بداية سطر النص وإيقاف الجدولة الأول. |
| [getFormatFlags()](#getFormatFlags--) | يحصل على تعداد  com.aspose.psd.StringFormatFlags  يحتوي على معلومات التنسيق. |
| [getGenericDefault()](#getGenericDefault--) | يحصل على كائن  com.aspose.psd.StringFormat  افتراضي عام. |
| [getGenericTypographic()](#getGenericTypographic--) | يحصل على كائن  com.aspose.psd.StringFormat  طباعي عام. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | يحصل على كائن  com.aspose.psd.HotkeyPrefix  لهذا الكائن  com.aspose.psd.StringFormat . |
| [getLineAlignment()](#getLineAlignment--) | يحصل على محاذاة السطر في المستوى الأفقي. |
| [getTabStops()](#getTabStops--) | يحصل على مصفوفة من المسافات بين إيقافات الجدولة بالوحدات المحددة بواسطة الخاصية  P:Aspose.Imaging.getGraphics().PageUnit . |
| [getTrimming()](#getTrimming--) | يحصل على تعداد  com.aspose.psd.StringTrimming  لهذا الكائن  com.aspose.psd.StringFormat . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | يضبط معلومات محاذاة النص في المستوى الرأسي. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | يضبط اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | يضبط الطريقة المستخدمة لاستبدال الأرقام. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | يضبط تعداد  com.aspose.psd.StringFormatFlags  يحتوي على معلومات التنسيق. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | يضبط كائن  com.aspose.psd.HotkeyPrefix  لهذا الكائن  com.aspose.psd.StringFormat . |
| [setLineAlignment(int value)](#setLineAlignment-int-) | يضبط محاذاة السطر في المستوى الأفقي. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | يضبط إيقافات الجدولة لهذا الكائن  com.aspose.psd.StringFormat . |
| [setTrimming(int value)](#setTrimming-int-) | يضبط تعداد com.aspose.psd.StringTrimming لهذا الكائن com.aspose.psd.StringFormat. |
| [toString()](#toString--) | يحوّل هذا الكائن com.aspose.psd.StringFormat إلى سلسلة قابلة للقراءة من قبل الإنسان. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


يُنشئ كائنًا جديدًا من  com.aspose.psd.StringFormat .

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


يُنشئ كائنًا جديدًا من  com.aspose.psd.StringFormat  مع تعداد  com.aspose.psd.StringFormatFlags  المحدد واللغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خيارات | int | تعداد com.aspose.psd.StringFormatFlags للكائن الجديد com.aspose.psd.StringFormat. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


يُنشئ كائنًا جديدًا من  com.aspose.psd.StringFormat  استنادًا إلى كائن  com.aspose.psd.StringFormat  الموجود المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | الكائن com.aspose.psd.StringFormat الذي يُستخدم لتهيئة الكائن الجديد com.aspose.psd.StringFormat. |

### close() {#close--}
```
public void close()
```


تنفيذ واجهة Closable ويمكن استخدامها في بيان try-with-resources منذ JDK 1.7. هذه الطريقة تستدعي ببساطة طريقة dispose.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


ينشئ نسخة عميقة من هذا الكائن  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


يحرر النسخة الحالية.

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


يحصل على معلومات محاذاة النص في المستوى الرأسي.

**Returns:**
int - تعداد com.aspose.psd.StringAlignment يحدد معلومات محاذاة النص.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


يحصل على اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية.

**Returns:**
int - معرف لغة دعم اللغة الوطنية (NLS) يحدد اللغة التي ستُستخدم عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. يمكنك تمرير الخاصية P:System.Globalization.CultureInfo.LCID لكائن System.Globalization.CultureInfo كمعرف لغة NLS. على سبيل المثال، افترض أنك تنشئ كائن System.Globalization.CultureInfo بتمرير السلسلة "ar-EG" إلى مُنشئ System.Globalization.CultureInfo. إذا مررت الخاصية P:System.Globalization.CultureInfo.LCID لذلك الكائن System.Globalization.CultureInfo مع com.aspose.psd.StringDigitSubstitute.Traditional إلى طريقة com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute)، فستُستبدل الأرقام العربية-الهندية بالأرقام الغربية عند العرض.

تم تقديم المُعيّن للطريقة القديمة setDigitSubstitution.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


يحصل على الطريقة المستخدمة لاستبدال الأرقام.

**Returns:**
int - قيمة تعداد com.aspose.psd.StringDigitSubstitute تحدد كيفية استبدال الأحرف في سلسلة لا يمكن عرضها لأنها غير مدعومة من الخط الحالي.

تم تقديم المُعيّن للطريقة القديمة SetDigitSubstitution.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه.

**Returns:**
boolean -  true  إذا تم التخلص؛ وإلا،  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


يحصل على عدد المسافات بين بداية سطر النص وإيقاف الجدولة الأول.

**Returns:**
float - إزاحة التبويب الأول.

تم تقديم الخاصية للطريقة المحذوفة GetTabStops.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


يحصل على تعداد  com.aspose.psd.StringFormatFlags  يحتوي على معلومات التنسيق.

**Returns:**
int - تعداد com.aspose.psd.StringFormatFlags يحتوي على معلومات التنسيق.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


يحصل على كائن  com.aspose.psd.StringFormat  افتراضي عام.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


يحصل على كائن  com.aspose.psd.StringFormat  طباعي عام.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


يحصل على كائن  com.aspose.psd.HotkeyPrefix  لهذا الكائن  com.aspose.psd.StringFormat .

**Returns:**
int - كائن com.aspose.psd.HotkeyPrefix لهذا الكائن com.aspose.psd.StringFormat، القيمة الافتراضية هي F:Aspose.Imaging.HotkeyPrefix.None.
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


يحصل على محاذاة السطر في المستوى الأفقي.

**Returns:**
int - تعداد com.aspose.psd.StringAlignment يمثل محاذاة السطر.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


يحصل على مصفوفة من المسافات بين إيقافات الجدولة بالوحدات المحددة بواسطة الخاصية  P:Aspose.Imaging.getGraphics().PageUnit .

**Returns:**
float[] - مواضع التبويبات.

تم تقديم الخاصية للطريقة المحذوفة GetTabStops.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


يحصل على تعداد  com.aspose.psd.StringTrimming  لهذا الكائن  com.aspose.psd.StringFormat .

**Returns:**
int - تعداد com.aspose.psd.StringTrimming يوضح كيفية تقليم النص المرسوم بهذا الكائن com.aspose.psd.StringFormat عندما يتجاوز حدود مستطيل التخطيط.
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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


يضبط معلومات محاذاة النص في المستوى الرأسي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تعداد com.aspose.psd.StringAlignment يحدد معلومات محاذاة النص. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


يضبط اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | معرف لغة دعم اللغة الوطنية (NLS) يحدد اللغة التي ستُستخدم عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. يمكنك تمرير الخاصية P:System.Globalization.CultureInfo.LCID لكائن System.Globalization.CultureInfo كمعرف لغة NLS. على سبيل المثال، افترض أنك تنشئ كائن System.Globalization.CultureInfo بتمرير السلسلة "ar-EG" إلى مُنشئ System.Globalization.CultureInfo. إذا مررت الخاصية P:System.Globalization.CultureInfo.LCID لذلك الكائن System.Globalization.CultureInfo مع com.aspose.psd.StringDigitSubstitute.Traditional إلى طريقة com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute)، فستُستبدل الأرقام العربية-الهندية بالأرقام الغربية عند العرض. |

تم تقديم المُعيّن للطريقة القديمة SetDigitSubstitution. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


يضبط الطريقة المستخدمة لاستبدال الأرقام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | قيمة تعداد com.aspose.psd.StringDigitSubstitute تحدد كيفية استبدال الأحرف في سلسلة لا يمكن عرضها لأنها غير مدعومة من الخط الحالي. |

تم تقديم المُعيّن للطريقة القديمة SetDigitSubstitution. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


يضبط تعداد  com.aspose.psd.StringFormatFlags  يحتوي على معلومات التنسيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تعداد com.aspose.psd.StringFormatFlags يحتوي على معلومات التنسيق. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


يضبط كائن  com.aspose.psd.HotkeyPrefix  لهذا الكائن  com.aspose.psd.StringFormat .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | كائن com.aspose.psd.HotkeyPrefix لهذا الكائن com.aspose.psd.StringFormat، القيمة الافتراضية هي F:Aspose.Imaging.HotkeyPrefix.None. |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


يضبط محاذاة السطر في المستوى الأفقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تعداد com.aspose.psd.StringAlignment يمثل محاذاة السطر. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


يضبط إيقافات الجدولة لهذا الكائن  com.aspose.psd.StringFormat .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| firstTabOffset | float | عدد الفراغات بين بداية سطر النص وأول موضع تبويب. |
| tabStops | float[] | مصفوفة من المسافات بين مواضِد التبويب بالوحدات المحددة بواسطة خاصية com.aspose.psd.Graphics.PageUnit. |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


يضبط تعداد com.aspose.psd.StringTrimming لهذا الكائن com.aspose.psd.StringFormat.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تعداد com.aspose.psd.StringTrimming يوضح كيفية تقليم النص المرسوم باستخدام كائن com.aspose.psd.StringFormat عندما يتجاوز حدود مستطيل التخطيط. |

### toString() {#toString--}
```
public String toString()
```


يحوّل هذا الكائن com.aspose.psd.StringFormat إلى سلسلة قابلة للقراءة من قبل الإنسان.

**Returns:**
java.lang.String - تمثيل نصي لهذا الكائن com.aspose.psd.StringFormat.
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

