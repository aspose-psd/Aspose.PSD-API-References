---
title: "IText"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Schnittstelle für die Textbearbeitung von Textebenen"
type: docs
weight: 11
url: /de/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Schnittstelle für die Textbearbeitung von Textebenen
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Fügt den Textabschnitt am Ende hinzu |
| [getItems()](#getItems--) | Liefert die Elemente. |
| [getText()](#getText--) | Liefert den Text. |
| [getTextOrientation()](#getTextOrientation--) | Liefert oder setzt die Textausrichtung. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Fügt die [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) an der angegebenen Position ein |
| [producePortion()](#producePortion--) | Erzeugt den neuen Abschnitt mit Standardparametern |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Erzeugt die neuen Abschnitte mit Eingabe- oder Standardparametern. |
| [removePortion(int index)](#removePortion-int-) | Entfernt den Abschnitt am angegebenen Index |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Liefert oder setzt die Textausrichtung. |
| [updateLayerData()](#updateLayerData--) | Aktualisiert die Ebenendaten. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Fügt den Textabschnitt am Ende hinzu

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Der Abschnitt. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Liefert die Elemente.

Wert: Die Elemente.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Liefert den Text.

Wert: Der Text.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Liefert oder setzt die Textausrichtung.

Wert: Die Textausrichtung.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Fügt die [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) an der angegebenen Position ein

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Der Abschnitt. |
| Index | int | Der Index. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Erzeugt den neuen Abschnitt mit Standardparametern

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Erzeugt die neuen Abschnitte mit Eingabe- oder Standardparametern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | Die Textabschnitte zum Erstellen neuer  ITextPortion . |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Ein Stil, der, falls nicht null, im neuen   angewendet wird, andernfalls wird er standardmäßig verwendet. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Ein Absatz, der, falls nicht null, im neuen   angewendet wird, andernfalls wird er standardmäßig verwendet. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Gibt die neuen Abschnitte  ITextPortion  basierend auf Eingabeparametern zurück.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Entfernt den Abschnitt am angegebenen Index

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Der Index. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Liefert oder setzt die Textausrichtung.

Wert: Die Textausrichtung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Aktualisiert die Ebenendaten.

