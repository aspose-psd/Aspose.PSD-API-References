---
title: "FontSettings فئة"
type: docs
weight: 1370
url: /ar/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | يحصل أو يعيّن الاسم الافتراضي للخط. |
| get_system_alternative_font [static] | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [get alternative font]. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| clear_font_replacements() | يمسح جميع استبدالات الخطوط |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | يحصل على اسم خط أدوبي بناءً على اسم عائلة الخط. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | يحصل على مجلدات الخطوط الافتراضية. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | يحصل على مصفوفة استبدالات الخط بناءً على اسم الخط |
| [get_fonts_folders()](#get_fonts_folders__4) | يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات التي يبحث فيها Aspose.Words عن خطوط TrueType. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | يحصل على الخط البديل الأنسب.<br/>            إذا لم يُسمح بجميع الاستبدالات فسيتم إرجاع أول خط مسموح ومتوفر.<br/>            إذا لم تكن هناك خطوط متوفرة فسيتم إرجاع الخط من الوسيط. |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | يحدد ما إذا كان [is font allowed] [the specified font name]. |
| remove_font_cache_file() | يزيل ملف ذاكرة التخزين المؤقت للخط. |
| reset() | يعيد تعيين مجلد الخطوط واسم الخط الافتراضي إلى الإعداد الافتراضي للنظام. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | يقيد استخدام الخط بقائمة من الخطوط. يرجى التحقق من أسماء الخطوط الفعلية قبل القيد<br/>            اضبط قائمة الخطوط المسموح بها إلى Null لإزالة القيود |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | يضبط قائمة استبدال الخطوط. إذا لم يكن الخط مسموحًا به فسيتم العثور على بديل.<br/>            سيتم استخدام أول خط في القائمة أولاً. إذا كان مقيدًا أيضًا، فسيتم اختيار الخط التالي من القائمة.<br/>            إذا لم يكن للخط بدائل أو جميع البدائل غير مسموح بها، فسيتم استخدام أول خط مسموح به من قائمة الخطوط المسموح بها.<br/>            إذا لم توجد خطوط مسموح بها ومتاحة، فستحاول المكتبة استخدام الخط الافتراضي للنظام حتى وإن لم يكن مسموحًا به. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | هذا اختصار إلى [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) لتعيين دليل خط واحد فقط.<br/>            لا يتم إجراء أي فحوصات على مجلد الخطوط. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | يضبط المجلدات التي تُحمَّل منها خطوط TrueType ويُمسح جميع الخطوط المحملة.<br/>            لا يتم إجراء أي فحوصات على مجلدات الخطوط. |
| update_fonts() | يقوم بتحديث ذاكرة التخزين المؤقت للخطوط لملفات PSD التي تحتوي على طبقات نصية. تضمن هذه الطريقة أن الخطوط من المجلد fontsFolder باستخدام<br/>            طريقة FontSettings.SetFontsFolder(fontsFolder) أو بعد إعادة تعيين الخطوط باستخدام FontSettings.Reset() سيتم أخذها في الاعتبار عند معالجة ملفات PSD. يرجى استخدام هذه الطريقة في كل مرة عندما <br/>            يتم استدعاء FontSettings.SetFontsFolder(fontsFolder) أو FontSettings.Reset() لصور PSD. دون استدعاء هذه الطريقة لا يوجد ضمان بتحديث الخطوط. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

يحصل على اسم خط أدوبي بناءً على اسم عائلة الخط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_family_name | string | اسم عائلة الخط. |

**Returns**

| النوع | الوصف |
| :- | :- |
| string | اسم خط أدوبي حسب اسم عائلة الخط. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

يحصل على مجلدات الخطوط الافتراضية.

**Returns**

| النوع | الوصف |
| :- | :- |
| string | يرجع مجلد النظام |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

يحصل على مصفوفة استبدالات الخط بناءً على اسم الخط

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_name | string | اسم الخط. |

**Returns**

| النوع | الوصف |
| :- | :- |
| string | مصفوفة بأسماء البدائل للخطوط المقدمة |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات التي يبحث فيها Aspose.Words عن خطوط TrueType.

**Returns**

| النوع | الوصف |
| :- | :- |
| string | نسخة من مواقع الخطوط الحالية. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

يحصل على الخط البديل الأنسب.<br/>            إذا لم يُسمح بجميع الاستبدالات فسيتم إرجاع أول خط مسموح ومتوفر.<br/>            إذا لم تكن هناك خطوط متوفرة فسيتم إرجاع الخط من الوسيط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_name | string | اسم الخط. |

**Returns**

| النوع | الوصف |
| :- | :- |
| string | اسم الخط المستبدل |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

يحدد ما إذا كان [is font allowed] [the specified font name].

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_name | string | اسم الخط. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان [is font allowed] [اسم الخط المحدد]; وإلا، <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

يقيد استخدام الخط بقائمة من الخطوط. يرجى التحقق من أسماء الخطوط الفعلية قبل القيد<br/>            اضبط قائمة الخطوط المسموح بها إلى Null لإزالة القيود

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_list | string | قائمة الخطوط. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

يضبط قائمة استبدال الخطوط. إذا لم يكن الخط مسموحًا به فسيتم العثور على بديل.<br/>            سيتم استخدام أول خط في القائمة أولاً. إذا كان مقيدًا أيضًا، فسيتم اختيار الخط التالي من القائمة.<br/>            إذا لم يكن للخط بدائل أو جميع البدائل غير مسموح بها، فسيتم استخدام أول خط مسموح به من قائمة الخطوط المسموح بها.<br/>            إذا لم توجد خطوط مسموح بها ومتاحة، فستحاول المكتبة استخدام الخط الافتراضي للنظام حتى وإن لم يكن مسموحًا به.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_to_replace | string | الخط المراد استبداله. |
| font_names | string | أسماء الخطوط البديلة بترتيب التشابه. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

هذا اختصار إلى [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) لتعيين دليل خط واحد فقط.<br/>            لا يتم إجراء أي فحوصات على مجلد الخطوط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| font_folder | string | مجلد الخط. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

يضبط المجلدات التي تُحمَّل منها خطوط TrueType ويُمسح جميع الخطوط المحملة.<br/>            لا يتم إجراء أي فحوصات على مجلدات الخطوط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| fonts_folders | string | مجلدات الخطوط. |
| متكرر | bool | إذا تم تعيينه إلى <c>true</c> [recursive]. |

