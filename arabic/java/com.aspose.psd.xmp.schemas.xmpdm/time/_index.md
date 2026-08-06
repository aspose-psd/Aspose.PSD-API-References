---
title: "Time"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تمثيل قيمة زمنية بالثواني."
type: docs
weight: 13
url: /ar/java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

تمثيل قيمة زمنية بالثواني.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | يقوم بإنشاء نسخة جديدة من الفئة Time. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | يحصل أو يضبط المقياس لقيمة الوقت. |
| [getValue()](#getValue--) | يحصل أو يضبط قيمة الوقت بالمقياس المحدد. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يحصل على القيمة النصية المحتواة بتنسيق XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | يحصل أو يضبط المقياس لقيمة الوقت. |
| [setValue(int value)](#setValue-int-) | يحصل أو يضبط قيمة الوقت بالمقياس المحدد. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


يقوم بإنشاء نسخة جديدة من الفئة Time.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | المقياس. |
| القيمة | int | القيمة. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getScale() {#getScale--}
```
public Rational getScale()
```


يحصل أو يضبط المقياس لقيمة الوقت.

لـ NTSC، استخدم 1001/30000، أو القيمة الأقل دقة 100/2997. لـ PAL، استخدم 1/25. القيمة: المقياس لقيمة الوقت.

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


يحصل أو يضبط قيمة الوقت بالمقياس المحدد.

القيمة: قيمة الوقت بالمقياس المحدد.

**Returns:**
int
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يحصل على القيمة النصية المحتواة بتنسيق XMP.

**Returns:**
java.lang.String - يُرجِع القيمة النصية المحتواة بتنسيق XMP.
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




### setScale(Rational value) {#setScale-com.aspose.psd.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


يحصل أو يضبط المقياس لقيمة الوقت.

لـ NTSC، استخدم 1001/30000، أو القيمة الأقل دقة 100/2997. لـ PAL، استخدم 1/25. القيمة: المقياس لقيمة الوقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


يحصل أو يضبط قيمة الوقت بالمقياس المحدد.

القيمة: قيمة الوقت بالمقياس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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

