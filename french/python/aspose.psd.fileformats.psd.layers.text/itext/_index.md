---
title: "Classe IText"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Obtient les éléments. |
| text | chaîne | r | Obtient le texte. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Obtient ou définit l'orientation du texte. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Ajoute la portion de texte à la fin |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Insère le [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) à la position spécifiée |
| [produce_portion()](#produce_portion__3) | Produit la nouvelle portion avec les paramètres par défaut |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Produit les nouvelles portions avec des paramètres d'entrée ou par défaut. |
| [remove_portion(index)](#remove_portion_index_5) | Supprime la portion à l'index spécifié |
| update_layer_data() | Met à jour les données du calque. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Ajoute la portion de texte à la fin

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | La portion. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Insère le [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) à la position spécifiée

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | La portion. |
| index | int | L'index. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Produit la nouvelle portion avec les paramètres par défaut

**Returns**

| Type | Description |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Référence au [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) nouvellement créé. |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Produit les nouvelles portions avec des paramètres d'entrée ou par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| portions_of_text | string | Les portions de texte pour créer un nouveau [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Un style qui, s'il n'est pas nul, sera appliqué dans le nouveau [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), sinon sera par défaut. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Un paragraphe qui, s'il n'est pas nul, sera appliqué dans le nouveau [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), sinon il sera par défaut. |

**Returns**

| Type | Description |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Renvoie les nouvelles portions [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) basées sur les paramètres d'entrée. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Supprime la portion à l'index spécifié

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index. |

