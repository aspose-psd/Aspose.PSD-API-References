---
title: "الفئة ITextStyle"
type: docs
weight: 40
url: /ar/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | يحصل أو يضبط التباعد التلقائي. |
| auto_leading | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [automatic leading]. |
| baseline_shift | double | r/w | إزاحة الخط الأساسي. |
| contextual_alternates | bool | r/w | البدائل السياقية المستخدمة لربط الأحرف معًا. |
| discretionary_ligatures | bool | r/w | الروابط الاختيارية المستخدمة لربط الأحرف، خاصةً في الخطوط المكتوبة. |
| faux_bold | bool | r/w | يحصل أو يضبط ما إذا كان faux bold مفعلاً. |
| faux_italic | bool | r/w | يحصل أو يضبط ما إذا كان faux bold مفعلاً. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يضبط لون التعبئة. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | خط الأساس للخط. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | حروف الخط الكبيرة. |
| font_index | int | r | يحصل على فهرس الخط. |
| font_name | string | r/w | يحصل أو يعيّن اسم الخط. |
| font_size | double | r/w | يحصل أو يضبط حجم الخط. |
| fractions | bool | r/w | يمكن استبدال رموز الكسور برمز خاص. |
| hindi_numbers | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [hindi numbers]. |
| horizontal_scale | double | r/w | المقياس الأفقي. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | يحصل أو يضبط محاذاة الرومانية العمودية القياسية.<br/>            هذا يعتمد على قيمة مورد BaselineDirection ويطبق فقط عندما يكون اتجاه النص هو [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/). |
| kerning | int | r/w | يحصل أو يضبط التباعد بين الأحرف. |
| language_index | int | r | يحصل على فهرس اللغة. |
| المسافة البادئة | double | r/w | يحصل أو يضبط المسافة البادئة. |
| no_break | bool | r/w | يحصل أو يضبط قيمة عدم الانقطاع. |
| standard_ligatures | bool | r/w | الروابط السياقية القياسية المستخدمة لربط الأحرف معًا. |
| تشطيب | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [تشطيب]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يضبط لون الخط. |
| تتبع | int | r/w | يحصل أو يضبط التتبع. |
| تسطير | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [تسطير]. |
| vertical_scale | double | r/w | المقياس العمودي. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [apply(style)](#apply_style_1) | يطبق النمط المحدد. |
| [is_equal(style)](#is_equal_style_2) | يحدد ما إذا كان النمط المحدد متساويًا. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

يطبق النمط المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | النمط. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

يحدد ما إذا كان النمط المحدد متساويًا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | النمط. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان النمط المحدد متساويًا؛ وإلا، <c>false</c>. |


