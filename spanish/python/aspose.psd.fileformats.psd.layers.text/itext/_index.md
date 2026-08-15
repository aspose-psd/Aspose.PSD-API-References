---
title: "Clase IText"
type: docs
weight: 10
url: /es/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Obtiene los elementos. |
| text | string | r | Obtiene el texto. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Obtiene o establece la orientación del texto. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Agrega la porción de texto al final |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Inserta el [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) en la posición especificada |
| [produce_portion()](#produce_portion__3) | Produce la nueva porción con parámetros predeterminados |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Produce las nuevas porciones con parámetros de entrada o predeterminados. |
| [remove_portion(index)](#remove_portion_index_5) | Elimina la porción en el índice especificado |
| update_layer_data() | Actualiza los datos de la capa. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Agrega la porción de texto al final

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | La porción. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Inserta el [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) en la posición especificada

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | La porción. |
| index | int | El índice. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Produce la nueva porción con parámetros predeterminados

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Referencia a la [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) recién creada. |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Produce las nuevas porciones con parámetros de entrada o predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| portions_of_text | string | Las porciones de texto para crear una nueva [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Un estilo que, si no es nulo, se aplicará en la nueva [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), de lo contrario será el predeterminado. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Un párrafo que, si no es nulo, se aplicará en el nuevo [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), de lo contrario será el predeterminado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Devuelve las nuevas porciones [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) basadas en los parámetros de entrada. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Elimina la porción en el índice especificado

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice. |

