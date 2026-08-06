---
title: "Blend"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحدد نمط المزج."
type: docs
weight: 11
url: /ar/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

يحدد نمط دمج. لا يمكن وراثة هذه الفئة.

الاستخدام النموذجي لفئة Blend هو تعريف نمط دمج للفرشاة. وبالتالي يجب تهيئة خصائص الدمج بعناية. لا يُسمح بالمصفوفات الفارغة. ستطلق الفرشاة الاستثناء المناسب إذا كانت مصفوفة عوامل الدمج أو مصفوفة المواقع فارغة أو إذا لم يكن طولهما متساويًا. إذا كان هناك عنصران أو أكثر في مصفوفة المواقع يجب أن يكون العنصر الأول 0 والأخير 1.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Blend()](#Blend--) | ينشئ مثيلًا جديدًا لفئة Blend. |
| [Blend(int count)](#Blend-int-) | ينشئ مثيلًا جديدًا لفئة Blend مع عدد العوامل والمواقع المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص ما إذا كان الكائن المحدد من فئة com.aspose.psd.Blend ومكافئ لهذه الفئة com.aspose.psd.Blend. |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | يحصل على مصفوفة عوامل المزج للانحدار. |
| [getPositions()](#getPositions--) | يحصل على مصفوفة مواضع المزج للانحدار. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | يضبط مصفوفة عوامل المزج للانحدار. |
| [setPositions(float[] value)](#setPositions-float---) | يضبط مصفوفة مواضع المزج للانحدار. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


ينشئ مثيلاً جديداً من الفئة  Blend . سيكون عدد العناصر في مصفوفتي العامل والمزج مساوياً لـ 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


ينشئ مثيلًا جديدًا لفئة Blend مع عدد العوامل والمواقع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| count | int | عدد العناصر في مصفوفتي العامل والموضع. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص ما إذا كان الكائن المحدد من فئة com.aspose.psd.Blend ومكافئ لهذه الفئة com.aspose.psd.Blend.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للاختبار. |

**Returns:**
منطقي - صحيح إذا كان  obj  من فئة  com.aspose.psd.Blend  مكافئًا لهذه الفئة  com.aspose.psd.Blend ; وإلا، خطأ.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFactors() {#getFactors--}
```
public float[] getFactors()
```


يحصل على مصفوفة عوامل المزج للانحدار.

**Returns:**
float[] - مصفوفة عوامل المزج التي تحدد نسب اللون الابتدائي واللون النهائي لاستخدامها في الموضع المقابل.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


يحصل على مصفوفة مواضع المزج للانحدار.

**Returns:**
float[] - مصفوفة مواضع المزج التي تحدد نسب المسافة على طول خط الانحدار.
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




### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


يضبط مصفوفة عوامل المزج للانحدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float[] | مصفوفة عوامل المزج التي تحدد نسب اللون الابتدائي واللون النهائي لاستخدامها في الموضع المقابل. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


يضبط مصفوفة مواضع المزج للانحدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float[] | مصفوفة مواضع المزج التي تحدد نسب المسافة على طول خط الانحدار. |

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

