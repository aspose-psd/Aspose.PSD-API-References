---
title: "IText"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Interfaccia per la modifica del testo per i livelli di testo"
type: docs
weight: 11
url: /it/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Interfaccia per la modifica del testo per i livelli di testo
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Aggiunge la porzione di testo alla fine |
| [getItems()](#getItems--) | Ottiene gli elementi. |
| [getText()](#getText--) | Ottiene il testo. |
| [getTextOrientation()](#getTextOrientation--) | Ottiene o imposta l'orientamento del testo. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Inserisce il [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) nella posizione specificata |
| [producePortion()](#producePortion--) | Crea la nuova porzione con i parametri predefiniti |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Crea le nuove porzioni con parametri di input o predefiniti. |
| [removePortion(int index)](#removePortion-int-) | Rimuove la porzione all'indice specificato |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Ottiene o imposta l'orientamento del testo. |
| [updateLayerData()](#updateLayerData--) | Aggiorna i dati del livello. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Aggiunge la porzione di testo alla fine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | La porzione. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Ottiene gli elementi.

Valore: gli elementi.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Ottiene il testo.

Valore: il testo.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Ottiene o imposta l'orientamento del testo.

Valore: l'orientamento del testo.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Inserisce il [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) nella posizione specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | La porzione. |
| indice | int | L'indice. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Crea la nuova porzione con i parametri predefiniti

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Crea le nuove porzioni con parametri di input o predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | Le porzioni di testo per creare un nuovo  ITextPortion . |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Uno stile che, se non nullo, verrà applicato nel nuovo   , altrimenti sarà quello predefinito. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Un paragrafo che, se non nullo, verrà applicato nel nuovo   , altrimenti sarà quello predefinito. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Restituisce le nuove porzioni  ITextPortion  basate sui parametri di input.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Rimuove la porzione all'indice specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | L'indice. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Ottiene o imposta l'orientamento del testo.

Valore: l'orientamento del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Aggiorna i dati del livello.

