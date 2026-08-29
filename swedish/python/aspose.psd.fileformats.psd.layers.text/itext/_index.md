---
title: "IText-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Hämtar objekten. |
| text | string | r | Hämtar texten. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Hämtar eller anger textorienteringen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Lägger till textdelen i slutet |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Infogar [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) på angiven position |
| [produce_portion()](#produce_portion__3) | Skapar den nya delen med standardparametrar |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Skapar de nya delarna med inmatade eller standardparametrar. |
| [remove_portion(index)](#remove_portion_index_5) | Tar bort delen på angivet index |
| update_layer_data() | Uppdaterar lagrets data. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Lägger till textdelen i slutet

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Delen. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Infogar [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) på angiven position

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Delen. |
| index | int | Indexet. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Skapar den nya delen med standardparametrar

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Referens till nyss skapad [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Skapar de nya delarna med inmatade eller standardparametrar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| portions_of_text | string | Textdelarna för att skapa ny [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | En stil som, om den inte är null, kommer att tillämpas i den nya [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), annars blir den standard. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Ett stycke som, om det inte är null, kommer att tillämpas i den nya [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), annars blir det standard. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Returnerar de nya delarna [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) baserat på inmatade parametrar. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Tar bort delen på angivet index

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Indexet. |

