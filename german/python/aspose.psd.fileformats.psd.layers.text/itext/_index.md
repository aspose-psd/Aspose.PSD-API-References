---
title: "IText Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Liest die Elemente. |
| text | string | r | Liest den Text. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Liest oder setzt die Textausrichtung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Fügt den Textabschnitt am Ende hinzu |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Fügt die [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) an der angegebenen Position ein |
| [produce_portion()](#produce_portion__3) | Erstellt den neuen Abschnitt mit Standardparametern |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Erstellt die neuen Abschnitte mit Eingabe- oder Standardparametern. |
| [remove_portion(index)](#remove_portion_index_5) | Entfernt den Abschnitt am angegebenen Index |
| update_layer_data() | Aktualisiert die Ebenendaten. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Fügt den Textabschnitt am Ende hinzu

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Der Abschnitt. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Fügt die [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) an der angegebenen Position ein

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Der Abschnitt. |
| index | int | Der Index. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Erstellt den neuen Abschnitt mit Standardparametern

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Verweis auf neu erstellte [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Erstellt die neuen Abschnitte mit Eingabe- oder Standardparametern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| portions_of_text | string | Die Textabschnitte zum Erstellen neuer [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Ein Stil, der, wenn er nicht null ist, im neuen [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) angewendet wird, andernfalls standardmäßig verwendet wird. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Ein Absatz, der, wenn er nicht null ist, im neuen [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) angewendet wird, andernfalls standardmäßig verwendet wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Gibt die neuen Abschnitte [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) basierend auf den Eingabeparametern zurück. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Entfernt den Abschnitt am angegebenen Index

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Index. |

