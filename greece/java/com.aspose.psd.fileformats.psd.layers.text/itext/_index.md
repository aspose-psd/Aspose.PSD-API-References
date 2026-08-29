---
title: "IText"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Διεπαφή για επεξεργασία κειμένου για Text Layers"
type: docs
weight: 11
url: /el/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Διεπαφή για επεξεργασία κειμένου για Text Layers
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Προσθέτει το τμήμα κειμένου στο τέλος |
| [getItems()](#getItems--) | Λαμβάνει τα στοιχεία. |
| [getText()](#getText--) | Λαμβάνει το κείμενο. |
| [getTextOrientation()](#getTextOrientation--) | Λαμβάνει ή ορίζει τον προσανατολισμό του κειμένου. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Εισάγει το [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) στη συγκεκριμένη θέση |
| [producePortion()](#producePortion--) | Δημιουργεί το νέο τμήμα με προεπιλεγμένες παραμέτρους |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Δημιουργεί τα νέα τμήματα με εισαγόμενες ή προεπιλεγμένες παραμέτρους. |
| [removePortion(int index)](#removePortion-int-) | Αφαιρεί το τμήμα στον καθορισμένο δείκτη |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Λαμβάνει ή ορίζει τον προσανατολισμό του κειμένου. |
| [updateLayerData()](#updateLayerData--) | Ενημερώνει τα δεδομένα του επιπέδου. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Προσθέτει το τμήμα κειμένου στο τέλος

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Το τμήμα. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Λαμβάνει τα στοιχεία.

Τιμή: Τα στοιχεία.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Λαμβάνει το κείμενο.

Τιμή: Το κείμενο.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Λαμβάνει ή ορίζει τον προσανατολισμό του κειμένου.

Τιμή: Ο προσανατολισμός του κειμένου.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Εισάγει το [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) στη συγκεκριμένη θέση

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Το τμήμα. |
| δείκτης | int | Ο δείκτης. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Δημιουργεί το νέο τμήμα με προεπιλεγμένες παραμέτρους

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Δημιουργεί τα νέα τμήματα με εισαγόμενες ή προεπιλεγμένες παραμέτρους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | Τα τμήματα κειμένου για τη δημιουργία νέου ITextPortion. |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Ένα στυλ που, εάν δεν είναι null, θα εφαρμοστεί στο νέο, διαφορετικά θα είναι προεπιλογή. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Μια παράγραφος που, εάν δεν είναι null, θα εφαρμοστεί στο νέο, διαφορετικά θα είναι προεπιλογή. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Επιστρέφει τα νέα τμήματα ITextPortion με βάση τις παραμέτρους εισόδου.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Αφαιρεί το τμήμα στον καθορισμένο δείκτη

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Ο δείκτης. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Λαμβάνει ή ορίζει τον προσανατολισμό του κειμένου.

Τιμή: Ο προσανατολισμός του κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Ενημερώνει τα δεδομένα του επιπέδου.

