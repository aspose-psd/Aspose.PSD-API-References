---
title: "فئة IText"
type: docs
weight: 10
url: /ar/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | يحصل على العناصر. |
| text | string | r | يحصل على النص. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | يحصل أو يضبط توجيه النص. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | يضيف جزء النص إلى النهاية |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | يدرج [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) في الموضع المحدد |
| [produce_portion()](#produce_portion__3) | ينتج الجزء الجديد باستخدام المعلمات الافتراضية |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | ينتج الأجزاء الجديدة باستخدام معلمات الإدخال أو الافتراضية. |
| [remove_portion(index)](#remove_portion_index_5) | يزيل الجزء في الفهرس المحدد |
| update_layer_data() | يقوم بتحديث بيانات الطبقة. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

يضيف جزء النص إلى النهاية

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | الجزء. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

يدرج [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) في الموضع المحدد

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | الجزء. |
| index | int | الفهرس. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

ينتج الجزء الجديد باستخدام المعلمات الافتراضية

**Returns**

| النوع | الوصف |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | إشارة إلى [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) الذي تم إنشاؤه حديثًا. |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

ينتج الأجزاء الجديدة باستخدام معلمات الإدخال أو الافتراضية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| portions_of_text | string | الأجزاء النصية لإنشاء [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) جديد. |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | نمط، إذا لم يكن فارغًا، سيُطبق في [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) الجديد، وإلا سيكون الافتراضي. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | فقرة إذا لم تكن فارغة، سيتم تطبيقها في الـ[ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)، وإلا ستكون افتراضية. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | يرجع الأجزاء الجديدة [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) بناءً على معلمات الإدخال. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

يزيل الجزء في الفهرس المحدد

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| index | int | الفهرس. |

