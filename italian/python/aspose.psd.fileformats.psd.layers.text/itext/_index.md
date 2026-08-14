---
title: "Classe IText"
type: docs
weight: 10
url: /it/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Ottiene gli elementi. |
| text | string | r | Ottiene il testo. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Ottiene o imposta l'orientamento del testo. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Aggiunge la porzione di testo alla fine |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Inserisce la [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) nella posizione specificata |
| [produce_portion()](#produce_portion__3) | Produce la nuova porzione con i parametri predefiniti |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Produce le nuove porzioni con parametri di input o predefiniti. |
| [remove_portion(index)](#remove_portion_index_5) | Rimuove la porzione all'indice specificato |
| update_layer_data() | Aggiorna i dati del livello. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Aggiunge la porzione di testo alla fine

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | La porzione. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Inserisce la [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) nella posizione specificata

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | La porzione. |
| index | int | L'indice. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Produce la nuova porzione con i parametri predefiniti

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Riferimento alla nuova [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Produce le nuove porzioni con parametri di input o predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| portions_of_text | string | Le porzioni di testo per creare una nuova [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Uno stile che, se non nullo, verrà applicato nella nuova [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), altrimenti sarà quello predefinito. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Un paragrafo che, se non nullo, verrà applicato nel nuovo [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), altrimenti sarà predefinito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Restituisce le nuove porzioni [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) in base ai parametri di input. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Rimuove la porzione all'indice specificato

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice. |

