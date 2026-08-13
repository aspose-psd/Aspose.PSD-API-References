---
title: "ITextParagraph 类"
type: docs
weight: 20
url: /zh/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---

**Summary:** The interface to work with paragraph

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextParagraph

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_hyphenate | bool | 读/写 | 获取或设置一个值，指示是否[automatic hyphenate]。 |
| auto_leading | double | 读/写 | 获取或设置自动行距。 |
| burasagari | bool | r/w | 获取或设置一个值，指示此[ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/)是否为burasagiri。 |
| consecutive_hyphens | int | 读/写 | 获取或设置连续连字符。 |
| end_indent | double | 读/写 | 获取或设置末尾缩进。 |
| every_line_composer | bool | 读/写 | 获取或设置一个值，指示是否[every line composer]。 |
| first_line_indent | double | 读/写 | 获取或设置首行缩进。 |
| glyph_spacing | double | 读/写 | 获取或设置字形间距。 |
| hanging | bool | r/w | 获取或设置一个值，指示此[ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/)是否为悬挂。 |
| hyphenated_word_size | int | 读/写 | 获取或设置连字符单词的大小。 |
| justification | [JustificationMode](/psd/python-net/aspose.psd.fileformats.psd/justificationmode) | r/w | 获取或设置对齐方式。 |
| kinsoku_order | int | 读/写 | 获取或设置禁则顺序。 |
| leading_type | [LeadingType](/psd/python-net/aspose.psd.fileformats.psd/leadingtype) | r/w | 获取或设置行距的类型。 |
| letter_spacing | double | 读/写 | 获取或设置字母间距。 |
| post_hyphen | int | 读/写 | 获取或设置后置连字符。 |
| pre_hyphen | int | 读/写 | 获取或设置前置连字符。 |
| space_after | double | 读/写 | 获取或设置后置空格。 |
| space_before | double | 读/写 | 获取或设置前置空格。 |
| start_indent | double | 读/写 | 获取或设置起始缩进。 |
| word_spacing | double | 读/写 | 获取或设置单词间距。 |
| zone | double | 读/写 | 获取或设置区域。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply(paragraph)](#apply_paragraph_1) | 应用指定的段落。 |
| [is_equal(paragraph)](#is_equal_paragraph_2) | 确定指定的段落是否相等。 |


### Method: apply(paragraph) {#apply_paragraph_1}


```
 apply(paragraph) 
```

应用指定的段落。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | 段落。 |

### Method: is_equal(paragraph) {#is_equal_paragraph_2}


```
 is_equal(paragraph) 
```

确定指定的段落是否相等。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | 段落。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果指定的段落相等；否则为 <c>false</c>。 |


