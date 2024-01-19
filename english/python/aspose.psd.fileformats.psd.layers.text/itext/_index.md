---
title: IText Class
type: docs
weight: 10
url: /python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 23.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Gets the items. |
| text | string | r | Gets the text. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Gets or sets the text orientation. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Adds the portion of text to the end |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Inserts the [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) to specified position |
| [produce_portion()](#produce_portion__3) | Produces the new portion with default parameters |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Produces the new portions with input or default parameters. |
| [remove_portion(index)](#remove_portion_index_5) | Removes the portion in specified index |
| update_layer_data() | Updates the layer data. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Adds the portion of text to the end

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | The portion. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Inserts the [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) to specified position

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | The portion. |
| index | int | The index. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Produces the new portion with default parameters

**Returns**

| Type | Description |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Reference to newly created [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Produces the new portions with input or default parameters.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| portions_of_text | string | The portions of text to create new [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | A style that, if not null, will be applied in the new [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), otherwise will be default. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | A paragraph that, if not null, will be applied in the new [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), otherwise will be default. |

**Returns**

| Type | Description |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Returns the new portions [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) based on input parameters. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Removes the portion in specified index

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The index. |

