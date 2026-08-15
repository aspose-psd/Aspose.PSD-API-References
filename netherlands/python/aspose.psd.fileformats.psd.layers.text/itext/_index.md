---
title: "IText Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Haalt de items op. |
| text | string | r | Haalt de tekst op. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Haalt de tekstoriëntatie op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Voegt het tekstgedeelte toe aan het einde |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Voegt de [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) in op de opgegeven positie |
| [produce_portion()](#produce_portion__3) | Produceert het nieuwe gedeelte met standaardparameters |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Produceert de nieuwe gedeelten met ingevoerde of standaardparameters. |
| [remove_portion(index)](#remove_portion_index_5) | Verwijdert het gedeelte op de opgegeven index |
| update_layer_data() | Werkt de laaggegevens bij. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Voegt het tekstgedeelte toe aan het einde

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Het gedeelte. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Voegt de [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) in op de opgegeven positie

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Het gedeelte. |
| index | int | De index. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Produceert het nieuwe gedeelte met standaardparameters

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Verwijzing naar nieuw aangemaakte [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Produceert de nieuwe gedeelten met ingevoerde of standaardparameters.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| portions_of_text | string | De tekstgedeelten om een nieuwe [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) te maken. |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Een stijl die, indien niet null, wordt toegepast in de nieuwe [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), anders wordt de standaard gebruikt. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Een alinea die, als deze niet null is, wordt toegepast in de nieuwe [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), anders wordt deze standaard. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Retourneert de nieuwe [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)-gedeelten op basis van invoerparameters. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Verwijdert het gedeelte op de opgegeven index

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | De index. |

