---
title: "IText"
second_title: "Aspose.PSD för Java API-referens"
description: "Gränssnitt för textredigering för textlager"
type: docs
weight: 11
url: /sv/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Gränssnitt för textredigering för textlager
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Lägger till textdelen i slutet |
| [getItems()](#getItems--) | Hämtar objekten. |
| [getText()](#getText--) | Hämtar texten. |
| [getTextOrientation()](#getTextOrientation--) | Hämtar eller anger textorienteringen. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Infogar [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) på angiven position |
| [producePortion()](#producePortion--) | Skapar den nya delen med standardparametrar |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Skapar de nya delarna med indata eller standardparametrar. |
| [removePortion(int index)](#removePortion-int-) | Tar bort delen på angivet index |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Hämtar eller anger textorienteringen. |
| [updateLayerData()](#updateLayerData--) | Uppdaterar lagrets data. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Lägger till textdelen i slutet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Delen. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Hämtar objekten.

Värde: Objekten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Hämtar texten.

Värde: Texten.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Hämtar eller anger textorienteringen.

Värde: Textorienteringen.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Infogar [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) på angiven position

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Delen. |
| index | int | Indexet. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Skapar den nya delen med standardparametrar

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Skapar de nya delarna med indata eller standardparametrar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | De textdelarna för att skapa en ny ITextPortion. |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | En stil som, om den inte är null, kommer att tillämpas i den nya   , annars blir den standard. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Ett stycke som, om det inte är null, kommer att tillämpas i den nya   , annars blir det standard. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Returnerar de nya delarna  ITextPortion  baserat på inmatningsparametrar.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Tar bort delen på angivet index

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Hämtar eller anger textorienteringen.

Värde: Textorienteringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Uppdaterar lagrets data.

