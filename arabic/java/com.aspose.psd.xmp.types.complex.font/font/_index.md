---
title: "Font"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل خط XMP."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

يمثل خط XMP.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Font()](#Font--) | يُنشئ مثيلاً جديدًا من الفئة  Font  . |
| [Font(String fontFamily)](#Font-java.lang.String-) | يُنشئ مثيلاً جديدًا من الفئة  Font  . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | يضيف المفتاح المحدد. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | يحصل أو يعيّن مصفوفة أسماء الملفات للخطوط التي تُكوّن خطًا مركبًا. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | يحصل أو يعيّن واجهة الخط. |
| [getFontFamily()](#getFontFamily--) | يحصل أو يعيّن عائلة الخط. |
| [getFontFileName()](#getFontFileName--) | يحصل أو يعيّن اسم ملف الخط دون المسار الكامل. |
| [getFontName()](#getFontName--) | يحصل أو يعيّن اسم خط PostScript. |
| [getFontType()](#getFontType--) | يحصل أو يعيّن نوع الخط. |
| [getNamespaceUri()](#getNamespaceUri--) | يحصل على URI مساحة الاسم الافتراضية. |
| [getPrefix()](#getPrefix--) | يحصل على البادئة. |
| [getVersion()](#getVersion--) | يحصل أو يعيّن إصدار الخط. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يحصل على القيمة النصية المحتواة بتنسيق XMP. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الخط مركبًا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | يحصل أو يعيّن مصفوفة أسماء الملفات للخطوط التي تُكوّن خطًا مركبًا. |
| [setComposite(boolean value)](#setComposite-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الخط مركبًا. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | يحصل أو يعيّن واجهة الخط. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | يحصل أو يعيّن عائلة الخط. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | يحصل أو يعيّن اسم ملف الخط دون المسار الكامل. |
| [setFontName(String value)](#setFontName-java.lang.String-) | يحصل أو يعيّن اسم خط PostScript. |
| [setFontType(String value)](#setFontType-java.lang.String-) | يحصل أو يعيّن نوع الخط. |
| [setVersion(String value)](#setVersion-java.lang.String-) | يحصل أو يعيّن إصدار الخط. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


يُنشئ مثيلاً جديدًا من الفئة  Font  .

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


يُنشئ مثيلاً جديدًا من الفئة  Font  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontFamily | java.lang.String | عائلة الخط. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


يضيف المفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | java.lang.Object | القيمة التي سيتم الإضافة إليها. |

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
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


يحصل أو يعيّن مصفوفة أسماء الملفات للخطوط التي تُكوّن خطًا مركبًا.

القيمة: مصفوفة أسماء الملفات للخطوط التي تشكل خطًا مركبًا.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


يحصل أو يعيّن واجهة الخط.

القيمة: شكل الخط.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


يحصل أو يعيّن عائلة الخط.

القيمة: عائلة الخط.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


يحصل أو يعيّن اسم ملف الخط دون المسار الكامل.

القيمة: اسم ملف الخط بدون المسار الكامل.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


يحصل أو يعيّن اسم خط PostScript.

القيمة: اسم خط PostScript.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


يحصل أو يعيّن نوع الخط.

TrueType، Type 1، Open Type، وما إلى ذلك. القيمة: نوع الخط.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


يحصل على URI مساحة الاسم الافتراضية.

**Returns:**
java.lang.String - مساحة الاسم الافتراضية URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


يحصل على البادئة.

**Returns:**
java.lang.String - البادئة.
### getVersion() {#getVersion--}
```
public String getVersion()
```


يحصل أو يعيّن إصدار الخط.

/version للخطوط Type1 nameId 5 لـ Apple True Type و OpenType /CIDFontVersion للخطوط CID السلسلة الفارغة للخطوط النقطية القيمة: إصدار الخط.

**Returns:**
java.lang.String
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
### isComposite() {#isComposite--}
```
public boolean isComposite()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الخط مركبًا.

القيمة:  true  إذا كان هذا الخط مركبًا؛ وإلا،  false .

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




### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


يحصل أو يعيّن مصفوفة أسماء الملفات للخطوط التي تُكوّن خطًا مركبًا.

القيمة: مصفوفة أسماء الملفات للخطوط التي تشكل خطًا مركبًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الخط مركبًا.

القيمة:  true  إذا كان هذا الخط مركبًا؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


يحصل أو يعيّن واجهة الخط.

القيمة: شكل الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


يحصل أو يعيّن عائلة الخط.

القيمة: عائلة الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


يحصل أو يعيّن اسم ملف الخط دون المسار الكامل.

القيمة: اسم ملف الخط بدون المسار الكامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


يحصل أو يعيّن اسم خط PostScript.

القيمة: اسم خط PostScript.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


يحصل أو يعيّن نوع الخط.

TrueType، Type 1، Open Type، وما إلى ذلك. القيمة: نوع الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


يحصل أو يعيّن إصدار الخط.

/version للخطوط Type1 nameId 5 لـ Apple True Type و OpenType /CIDFontVersion للخطوط CID السلسلة الفارغة للخطوط النقطية القيمة: إصدار الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

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

