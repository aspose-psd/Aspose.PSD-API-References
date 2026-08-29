---
title: "IText"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Interface voor tekstbewerking voor tekstlagen"
type: docs
weight: 11
url: /nl/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Interface voor tekstbewerking voor tekstlagen
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Voegt het tekstgedeelte toe aan het einde |
| [getItems()](#getItems--) | Haalt de items op. |
| [getText()](#getText--) | Haalt de tekst op. |
| [getTextOrientation()](#getTextOrientation--) | Haalt of stelt de tekstoriëntatie in. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Voegt de [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) in op de opgegeven positie |
| [producePortion()](#producePortion--) | Produceert het nieuwe gedeelte met standaardparameters |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Produceert de nieuwe gedeelten met ingevoerde of standaardparameters. |
| [removePortion(int index)](#removePortion-int-) | Verwijdert het gedeelte op de opgegeven index |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Haalt of stelt de tekstoriëntatie in. |
| [updateLayerData()](#updateLayerData--) | Werkt de laaggegevens bij. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Voegt het tekstgedeelte toe aan het einde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Het gedeelte. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Haalt de items op.

Waarde: De items.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Haalt de tekst op.

Waarde: De tekst.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Haalt of stelt de tekstoriëntatie in.

Waarde: De tekstoriëntatie.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Voegt de [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) in op de opgegeven positie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Het gedeelte. |
| index | int | De index. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Produceert het nieuwe gedeelte met standaardparameters

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Produceert de nieuwe gedeelten met ingevoerde of standaardparameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | De tekstgedeelten om een nieuwe ITextPortion te maken. |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Een stijl die, indien niet null, wordt toegepast in de nieuwe   , anders wordt standaard. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Een alinea die, indien niet null, wordt toegepast in de nieuwe   , anders wordt standaard. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Retourneert de nieuwe ITextPortion-onderdelen op basis van invoerparameters.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Verwijdert het gedeelte op de opgegeven index

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Haalt of stelt de tekstoriëntatie in.

Waarde: De tekstoriëntatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Werkt de laaggegevens bij.

