---
title: "فئة Font"
type: docs
weight: 1340
url: /ar/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | ينشئ كائنًا جديدًا من [Font](/psd/python-net/aspose.psd/font/) باستخدام حجم محدد. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/)، ونمط الخط إلى [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | ينشئ كائنًا جديدًا من [Font](/psd/python-net/aspose.psd/font/) باستخدام حجم ونمط محددين. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | ينشئ كائنًا جديدًا من [Font](/psd/python-net/aspose.psd/font/) باستخدام حجم ونمط ووحدة محددين. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | ينشئ كائنًا جديدًا من [Font](/psd/python-net/aspose.psd/font/) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | يُهيئ [Font](/psd/python-net/aspose.psd/font/) جديدًا باستخدام حجم ووحدة محددين. مجموعة الأحرف مُعيَّنة إلى [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)، والنمط مُعيَّن إلى [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | يُهيئ [Font](/psd/python-net/aspose.psd/font/) جديدًا يستخدم [Font](/psd/python-net/aspose.psd/font/) الموجود المحدد وتعداد [FontStyle](/psd/python-net/aspose.psd/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bold | bool | r | يحصل على قيمة تُشير إلى ما إذا كان هذا [Font](/psd/python-net/aspose.psd/font/) غامقًا. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | يحصل على قيمة بايت تُحدد مجموعة الأحرف التي يستخدمها هذا [Font](/psd/python-net/aspose.psd/font/). |
| italic | bool | r | يحصل على قيمة تُشير إلى ما إذا كان هذا [Font](/psd/python-net/aspose.psd/font/) مائلًا. |
| name | string | r | يحصل على اسم الوجه لهذا [Font](/psd/python-net/aspose.psd/font/). |
| size | float | r | يحصل على حجم الـ em لهذا [Font](/psd/python-net/aspose.psd/font/) مقاسًا بالوحدات المحددة في خاصية [Font.unit](/psd/python-net/aspose.psd/font/). |
| strikeout | bool | r | يحصل على قيمة تُشير إلى ما إذا كان هذا [Font](/psd/python-net/aspose.psd/font/) يُحدِّد خطًا أفقيًا عبر الخط. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | يحصل على معلومات النمط لهذا [Font](/psd/python-net/aspose.psd/font/). |
| underline | bool | r | يحصل على قيمة تُشير إلى ما إذا كان هذا [Font](/psd/python-net/aspose.psd/font/) مُسطَّرًا. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | يحصل على وحدة القياس لهذا [Font](/psd/python-net/aspose.psd/font/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | ينشئ نسخة عميقة مطابقة تمامًا من هذا [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

ينشئ كائنًا جديدًا من [Font](/psd/python-net/aspose.psd/font/) باستخدام حجم محدد. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/)، ونمط الخط إلى [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | حجم الـ em، بالنقاط، للخط الجديد. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

ينشئ كائنًا جديدًا من [Font](/psd/python-net/aspose.psd/font/) باستخدام حجم ونمط محددين. يتم تعيين مجموعة الأحرف إلى [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)، ووحدة الرسومات إلى [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | حجم الـ em، بالنقاط، للخط الجديد. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | الـ [FontStyle](/psd/python-net/aspose.psd/fontstyle/) للخط الجديد. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

ينشئ كائنًا جديدًا من [Font](/psd/python-net/aspose.psd/font/) باستخدام حجم ونمط ووحدة محددين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | الـ [FontStyle](/psd/python-net/aspose.psd/fontstyle/) للخط الجديد. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | الـ [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) للخط الجديد. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

ينشئ كائنًا جديدًا من [Font](/psd/python-net/aspose.psd/font/) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | الـ [FontStyle](/psd/python-net/aspose.psd/fontstyle/) للخط الجديد. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | الـ [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) للخط الجديد. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | مجموعة أحرف لاستخدامها مع هذا الخط. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

يُهيئ [Font](/psd/python-net/aspose.psd/font/) جديدًا باستخدام حجم ووحدة محددين. مجموعة الأحرف مُعيَّنة إلى [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)، والنمط مُعيَّن إلى [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_name | string | تمثيل نصي لاسم [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل <paramref name="unit" />. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | الـ [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) للخط الجديد. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

يُهيئ [Font](/psd/python-net/aspose.psd/font/) جديدًا يستخدم [Font](/psd/python-net/aspose.psd/font/) الموجود المحدد وتعداد [FontStyle](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | الـ [Font](/psd/python-net/aspose.psd/font/) الموجود الحالي الذي يُنشأ منه الـ [Font](/psd/python-net/aspose.psd/font/) الجديد. |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | الـ [FontStyle](/psd/python-net/aspose.psd/fontstyle/) لتطبيقه على الـ [Font](/psd/python-net/aspose.psd/font/) الجديد. يمكن دمج قيم متعددة من تعداد [FontStyle](/psd/python-net/aspose.psd/fontstyle/) باستخدام عامل OR. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

ينشئ نسخة عميقة مطابقة تمامًا من هذا [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| النوع | الوصف |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | الـ [Font](/psd/python-net/aspose.psd/font/) الذي ينشئه هذه الطريقة. |


