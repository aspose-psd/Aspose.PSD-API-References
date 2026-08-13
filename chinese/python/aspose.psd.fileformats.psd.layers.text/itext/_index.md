---
title: "IText 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | 获取项目。 |
| text | 字符串 | r | 获取文本。 |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | 获取或设置文本方向。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | 将文本片段添加到末尾 |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | 在指定位置插入 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) |
| [produce_portion()](#produce_portion__3) | 使用默认参数生成新的片段 |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | 使用输入或默认参数生成新的片段。 |
| [remove_portion(index)](#remove_portion_index_5) | 删除指定索引处的片段 |
| update_layer_data() | 更新图层数据。 |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

将文本片段添加到末尾

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | 该片段。 |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

在指定位置插入 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | 该片段。 |
| index | int | 索引。 |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

使用默认参数生成新的片段

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | 对新创建的 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) 的引用。 |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

使用输入或默认参数生成新的片段。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| portions_of_text | string | 用于创建新 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) 的文本片段。 |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | 一种样式，如果不为 null，将应用于新的 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)，否则将使用默认值。 |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | 一个段落，如果不为 null，将应用于新的 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)，否则将使用默认值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | 根据输入参数返回新的 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) 片段。 |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

删除指定索引处的片段

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 索引。 |

