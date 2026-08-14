---
title: "IText Κλάση"
type: docs
weight: 10
url: /el/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Λαμβάνει τα στοιχεία. |
| text | string | r | Ανακτά το κείμενο. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Λαμβάνει ή ορίζει τον προσανατολισμό του κειμένου. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Προσθέτει το τμήμα κειμένου στο τέλος |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Εισάγει το [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) στην καθορισμένη θέση |
| [produce_portion()](#produce_portion__3) | Δημιουργεί το νέο τμήμα με προεπιλεγμένες παραμέτρους |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Δημιουργεί τα νέα τμήματα με εισαγόμενες ή προεπιλεγμένες παραμέτρους. |
| [remove_portion(index)](#remove_portion_index_5) | Αφαιρεί το τμήμα στον καθορισμένο δείκτη |
| update_layer_data() | Ενημερώνει τα δεδομένα του στρώματος. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Προσθέτει το τμήμα κειμένου στο τέλος

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Το τμήμα. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Εισάγει το [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) στην καθορισμένη θέση

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Το τμήμα. |
| index | int | Ο δείκτης. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Δημιουργεί το νέο τμήμα με προεπιλεγμένες παραμέτρους

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Αναφορά στο νεοδημιουργημένο [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Δημιουργεί τα νέα τμήματα με εισαγόμενες ή προεπιλεγμένες παραμέτρους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| portions_of_text | string | Τα τμήματα κειμένου για τη δημιουργία νέου [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Ένα στυλ που, εάν δεν είναι null, θα εφαρμοστεί στο νέο [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), διαφορετικά θα είναι προεπιλεγμένο. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Μια παράγραφος που, εάν δεν είναι null, θα εφαρμοστεί στη νέα [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), διαφορετικά θα είναι προεπιλεγμένη. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Επιστρέφει τις νέες ενότητες [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) βάσει των παραμέτρων εισόδου. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Αφαιρεί το τμήμα στον καθορισμένο δείκτη

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Ο δείκτης. |

