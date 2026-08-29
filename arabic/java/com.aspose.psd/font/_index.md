---
title: "Font"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحدد تنسيقًا معينًا للنص يتضمن نوع الخط وحجمه وسمات النمط."
type: docs
weight: 46
url: /ar/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط والحجم وسمات النمط. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | ينشئ كائنًا جديدًا من com.aspose.psd.Font يستخدم الخط الموجود المحدد com.aspose.psd.Font وتعداد com.aspose.psd.FontStyle. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | يقوم بتهيئة كائن جديد من  com.aspose.psd.Font  باستخدام حجم محدد. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | يقوم بتهيئة كائن جديد من  com.aspose.psd.Font  باستخدام حجم ونمط محددين. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | يقوم بتهيئة كائن جديد من  com.aspose.psd.Font  باستخدام حجم، نمط، وحدة، ومجموعة أحرف محددة. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | يقوم بتهيئة كائن جديد من  com.aspose.psd.Font  باستخدام حجم، نمط، ووحدة محددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة مطابقة تمامًا من هذا  Font . |
| [equals(Object obj)](#equals-java.lang.Object-) | يشير إلى ما إذا كان الكائن المحدد هو  com.aspose.psd.Font  ويحتوي على نفس قيم الخصائص مثل هذا  com.aspose.psd.Font . |
| [getBold()](#getBold--) | يحصل على قيمة تشير إلى ما إذا كان هذا  Font  غامقًا. |
| [getCharacterSet()](#getCharacterSet--) | يحصل على قيمة بايت تحدد مجموعة الأحرف التي يستخدمها هذا  Font . |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | يحصل على قيمة تشير إلى ما إذا كان هذا  Font  مائلًا. |
| [getName()](#getName--) | يحصل على اسم الوجه لهذا  Font . |
| [getSize()](#getSize--) | يحصل على حجم الـ em لهذا  Font  المقاس بالوحدات المحددة بواسطة الخاصية  P:Aspose.Imaging.Font.Unit . |
| [getStrikeout()](#getStrikeout--) | يحصل على قيمة تشير إلى ما إذا كان هذا  Font  يحدد خطًا أفقيًا عبر الخط. |
| [getStyle()](#getStyle--) | يحصل على معلومات النمط لهذا  Font . |
| [getUnderline()](#getUnderline--) | يحصل على قيمة تشير إلى ما إذا كان هذا  Font  تحته خط. |
| [getUnit()](#getUnit--) | يحصل على وحدة القياس لهذا  Font . |
| [hashCode()](#hashCode--) | يحصل على رمز التجزئة لهذا  com.aspose.psd.Font . |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | يقوم بتهيئة كائن جديد من  com.aspose.psd.Font  باستخدام حجم ووحدة محددين. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا قابلًا للقراءة البشرية لهذا  com.aspose.psd.Font . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


ينشئ كائنًا جديدًا من com.aspose.psd.Font يستخدم الخط الموجود المحدد com.aspose.psd.Font وتعداد com.aspose.psd.FontStyle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | الـ com.aspose.psd.Font  الموجود الذي سيتم إنشاء الـ com.aspose.psd.Font  الجديد منه. |
| newStyle | int | الـ com.aspose.psd.FontStyle  لتطبيقه على الـ com.aspose.psd.Font  الجديد. يمكن دمج قيم متعددة من تعداد  com.aspose.psd.FontStyle  باستخدام عامل OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


يقوم بتهيئة كائن جديد من  com.aspose.psd.Font  باستخدام حجم محدد. يتم تعيين مجموعة الأحرف إلى  F:Aspose.Imaging.CharacterSet.Default ، ووحدة الرسومات إلى  F:Aspose.Imaging.GraphicsUnit.Point ، ونمط الخط إلى  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | تمثيل نصي لاسم  com.aspose.psd.Font . |
| emSize | float | حجم الـ em، بالنقاط، للخط الجديد. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


يُهيئ كائنًا جديدًا من  com.aspose.psd.Font  باستخدام حجم ونمط محددين. يتم تعيين مجموعة الأحرف إلى  F:Aspose.Imaging.CharacterSet.Default ، ووحدة الرسومات إلى  F:Aspose.Imaging.GraphicsUnit.Point .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | تمثيل نصي لاسم  com.aspose.psd.Font . |
| emSize | float | حجم الـ em، بالنقاط، للخط الجديد. |
| النمط | int | الـ  com.aspose.psd.FontStyle  للخط الجديد. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


يقوم بتهيئة كائن جديد من  com.aspose.psd.Font  باستخدام حجم، نمط، وحدة، ومجموعة أحرف محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | تمثيل نصي لاسم  com.aspose.psd.Font . |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل  unit . |
| النمط | int | الـ  com.aspose.psd.FontStyle  للخط الجديد. |
| الوحدة | int | الـ  com.aspose.psd.GraphicsUnit  للخط الجديد. |
| characterSet | int | مجموعة أحرف لاستخدامها مع هذا الخط. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


يقوم بتهيئة كائن جديد من  com.aspose.psd.Font  باستخدام حجم، نمط، ووحدة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | تمثيل نصي لاسم  com.aspose.psd.Font . |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل  unit . |
| النمط | int | الـ  com.aspose.psd.FontStyle  للخط الجديد. |
| الوحدة | int | الـ  com.aspose.psd.GraphicsUnit  للخط الجديد. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


ينشئ نسخة عميقة مطابقة تمامًا من هذا  Font .

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يشير إلى ما إذا كان الكائن المحدد هو  com.aspose.psd.Font  ويحتوي على نفس قيم الخصائص مثل هذا  com.aspose.psd.Font .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للاختبار. |

**Returns:**
boolean - True إذا كان معامل  obj  هو  com.aspose.psd.Font  وله نفس قيم الخصائص مثل هذا  com.aspose.psd.Font ؛ وإلا، false.
### getBold() {#getBold--}
```
public boolean getBold()
```


يحصل على قيمة تشير إلى ما إذا كان هذا  Font  غامقًا.

**Returns:**
boolean - True إذا كان هذا  Font  عريضًا؛ وإلا، false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


يحصل على قيمة بايت تحدد مجموعة الأحرف التي يستخدمها هذا  Font .

**Returns:**
int - مجموعة أحرف يستخدمها هذا  Font .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


يحصل على قيمة تشير إلى ما إذا كان هذا  Font  مائلًا.

**Returns:**
boolean - True إذا كان هذا  Font  مائلًا؛ وإلا، false.
### getName() {#getName--}
```
public String getName()
```


يحصل على اسم الوجه لهذا  Font .

**Returns:**
java.lang.String - تمثيل نصي لاسم الوجه لهذا  Font .
### getSize() {#getSize--}
```
public float getSize()
```


يحصل على حجم الـ em لهذا  Font  المقاس بالوحدات المحددة بواسطة الخاصية  P:Aspose.Imaging.Font.Unit .

**Returns:**
float - حجم الـ em لهذا  Font .
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


يحصل على قيمة تشير إلى ما إذا كان هذا  Font  يحدد خطًا أفقيًا عبر الخط.

**Returns:**
boolean - True إذا كان لهذا  Font  خط أفقي يمر عبره؛ وإلا، false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


يحصل على معلومات النمط لهذا  Font .

**Returns:**
int - تعداد  FontStyle  يحتوي على معلومات النمط لهذا  Font .
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


يحصل على قيمة تشير إلى ما إذا كان هذا  Font  تحته خط.

**Returns:**
boolean - True إذا كان هذا  Font  تحته خط؛ وإلا، false.
### getUnit() {#getUnit--}
```
public int getUnit()
```


يحصل على وحدة القياس لهذا  Font .

**Returns:**
int - وحدة  GraphicsUnit  التي تمثل وحدة القياس لهذا  Font .
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على رمز التجزئة لهذا  com.aspose.psd.Font .

**Returns:**
int - رمز التجزئة لهذا  com.aspose.psd.Font .
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


يُهيئ كائنًا جديدًا من  com.aspose.psd.Font  باستخدام حجم ووحدة محددين. يتم تعيين مجموعة الأحرف إلى  F:Aspose.Imaging.CharacterSet.Default ، ويتم تعيين النمط إلى  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | تمثيل نصي لاسم  com.aspose.psd.Font . |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل  unit . |
| الوحدة | int | الـ  com.aspose.psd.GraphicsUnit  للخط الجديد. |

**Returns:**
[Font](../../com.aspose.psd/font)
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


يرجع تمثيلًا نصيًا قابلًا للقراءة البشرية لهذا  com.aspose.psd.Font .

**Returns:**
java.lang.String - سلسلة تمثل هذا  com.aspose.psd.Font .
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

