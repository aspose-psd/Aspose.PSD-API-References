---
title: "ColorComponent"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "مكوّن اللون هو تجريد فوق قيمة القناة وقيمة القناة."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

مكوّن اللون هو تجريد فوق قيمة القناة وقيمة القناة. أي لون يتكوّن من مصفوفة من ColorComponent
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | ينشئ مثلاً جديداً من الفئة [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | يحصل على عمق البت لـ Color Component/Channel |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | يحصل على وصف الـ Color Component |
| [getFullName()](#getFullName--) | يحصل على الاسم الكامل للـ color component مع الاسم والوصف المفصول بمسافات |
| [getName()](#getName--) | يحصل على اسم الـ color component. |
| [getPermittedFullNames()](#getPermittedFullNames--) | يحصل على الأسماء الكاملة المسموح بها. |
| [getValue()](#getValue--) | يحصل أو يعيّن القيمة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | يحصل أو يعيّن القيمة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


ينشئ مثلاً جديداً من الفئة [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). يرجى التحقق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitDepth | byte | عمق البت. |
| fullName | java.lang.String | الاسم الكامل. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


يحصل على عمق البت لـ Color Component/Channel

القيمة: عمق البت.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


يحصل على وصف الـ Color Component

القيمة: الوصف.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


يحصل على الاسم الكامل للـ color component مع الاسم والوصف المفصول بمسافات

القيمة: الاسم الكامل.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


يحصل على اسم الـ color component.

القيمة: الاسم.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


يحصل على الأسماء الكاملة المسموح بها.

القيمة: الأسماء الكاملة المسموح بها.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


يحصل أو يعيّن القيمة. يرجى ملاحظة أنه إذا حاولت تعيين قيمة أكبر مما يمكن تخزينه في عمق البت الحالي، ستحصل على استثناء.

القيمة: القيمة.

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


يحصل أو يعيّن القيمة. يرجى ملاحظة أنه إذا حاولت تعيين قيمة أكبر مما يمكن تخزينه في عمق البت الحالي، ستحصل على استثناء.

القيمة: القيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

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

