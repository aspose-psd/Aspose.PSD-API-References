---
title: "Класс ITextParagraph"
type: docs
weight: 20
url: /ru/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---

**Summary:** The interface to work with paragraph

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextParagraph

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| auto_hyphenate | bool | r/w | Получает или задает значение, указывающее, включено ли [automatic hyphenate]. |
| auto_leading | double | r/w | Получает или задает автоматический интерлиньяж. |
| burasagari | bool | r/w | Получает или задает значение, указывающее, является ли этот [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/) burasagiri. |
| consecutive_hyphens | int | r/w | Получает или задает последовательные дефисы. |
| end_indent | double | r/w | Получает или задает конечный отступ. |
| every_line_composer | bool | r/w | Получает или задает значение, указывающее, включён ли [every line composer]. |
| first_line_indent | double | r/w | Получает или задает отступ первой строки. |
| glyph_spacing | double | r/w | Получает или задает интервал между глифами. |
| hanging | bool | r/w | Получает или задает значение, указывающее, является ли этот [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/) висячим. |
| hyphenated_word_size | int | r/w | Получает или задает размер переносимого слова. |
| justification | [JustificationMode](/psd/python-net/aspose.psd.fileformats.psd/justificationmode) | r/w | Получает или задает выравнивание. |
| kinsoku_order | int | r/w | Получает или задает порядок kinsoku. |
| leading_type | [LeadingType](/psd/python-net/aspose.psd.fileformats.psd/leadingtype) | r/w | Получает или задает тип межстрочного интервала. |
| letter_spacing | double | r/w | Получает или задает межбуквенный интервал. |
| post_hyphen | int | r/w | Получает или задает постдефис. |
| pre_hyphen | int | r/w | Получает или задает преддефис. |
| space_after | double | r/w | Получает или задает пробел после. |
| space_before | double | r/w | Получает или задает пробел перед. |
| start_indent | double | r/w | Получает или задает начальный отступ. |
| word_spacing | double | r/w | Получает или задает межсловный интервал. |
| zone | double | r/w | Получает или задает зону. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [apply(paragraph)](#apply_paragraph_1) | Применяет указанный абзац. |
| [is_equal(paragraph)](#is_equal_paragraph_2) | Определяет, равен ли указанный абзац. |


### Method: apply(paragraph) {#apply_paragraph_1}


```
 apply(paragraph) 
```

Применяет указанный абзац.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Абзац. |

### Method: is_equal(paragraph) {#is_equal_paragraph_2}


```
 is_equal(paragraph) 
```

Определяет, равен ли указанный абзац.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Абзац. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если указанный абзац равен; иначе <c>false</c>. |


