---
title: "فئة StringFormat"
type: docs
weight: 4260
url: /ar/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | ينشئ كائنًا جديدًا من النوع [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | ينشئ كائنًا جديدًا من النوع [StringFormat](/psd/python-net/aspose.psd/stringformat/) من الكائن [StringFormat](/psd/python-net/aspose.psd/stringformat/) الموجود المحدد. |
| [StringFormat(options)](#StringFormat_options_3) | ينشئ كائنًا جديدًا من النوع [StringFormat](/psd/python-net/aspose.psd/stringformat/) باستخدام تعداد [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) واللغة المحددة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | يحصل أو يضبط معلومات محاذاة النص على المستوى الرأسي. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | يحصل أو يضبط معرف الحرف المخصص. |
| digit_substitution_language | int | r/w | يحصل أو يضبط اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | يحصل أو يضبط الطريقة التي ستُستخدم لاستبدال الأرقام. |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| first_tab_offset | float | r | يحصل على عدد الفراغات بين بداية سطر النص وأول موضع تبويب. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | يحصل أو يضبط تعداد [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) الذي يحتوي على معلومات التنسيق. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | يحصل على كائن [StringFormat](/psd/python-net/aspose.psd/stringformat/) افتراضي عام. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | يحصل على كائن [StringFormat](/psd/python-net/aspose.psd/stringformat/) طباعي عام. |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | يحصل أو يضبط كائن [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) لهذا الكائن [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | يحصل أو يضبط محاذاة السطر على المستوى الأفقي. |
| tab_stops | float | r | يحصل على مصفوفة من المسافات بين مواضع التبويب بالوحدات المحددة بواسطة الخاصية [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | يحصل أو يضبط تعداد [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) لهذا الكائن [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | ينشئ نسخة عميقة من هذا الكائن [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | يضبط مواضع التبويب لهذا الكائن [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

ينشئ كائنًا جديدًا من النوع [StringFormat](/psd/python-net/aspose.psd/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

ينشئ كائنًا جديدًا من النوع [StringFormat](/psd/python-net/aspose.psd/stringformat/) من الكائن [StringFormat](/psd/python-net/aspose.psd/stringformat/) الموجود المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | الكائن [StringFormat](/psd/python-net/aspose.psd/stringformat/) الذي يُستخدم لتهيئة الكائن الجديد [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

ينشئ كائنًا جديدًا من النوع [StringFormat](/psd/python-net/aspose.psd/stringformat/) باستخدام تعداد [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) واللغة المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | تعداد [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) للكائن الجديد [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

ينشئ نسخة عميقة من هذا الكائن [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Returns**

| النوع | الوصف |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | النسخة العميقة من الكائن الحالي [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

يضبط مواضع التبويب لهذا الكائن [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| first_tab_offset | float | عدد الفراغات بين بداية سطر النص وأول موضع تبويب. |
| tab_stops | float | مصفوفة من المسافات بين مواضع التبويب بالوحدات المحددة بواسطة الخاصية [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |

