---
title: "IPathShape"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La forma dai nodi della curva Bézier."
type: docs
weight: 31
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

La forma dai nodi della curva Bézier.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getItems()](#getItems--) | Ottiene l'array di nodi Bezier. |
| [getPathOperations()](#getPathOperations--) | Le operazioni per la combinazione delle forme del percorso (operazioni booleane). |
| [isClosed()](#isClosed--) | Ottiene o imposta la proprietà che determina se la Forma è chiusa. |
| [setClosed(boolean value)](#setClosed-boolean-) | Ottiene o imposta la proprietà che determina se la Forma è chiusa. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Assegna un array di nodi Bexier. |
| [setPathOperations(int value)](#setPathOperations-int-) | Le operazioni per la combinazione delle forme del percorso (operazioni booleane). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Ottiene l'array di nodi Bezier.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Array di BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


Le operazioni per la combinazione delle forme del percorso (operazioni booleane).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Ottiene o imposta la proprietà che determina se la Forma è chiusa.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Ottiene o imposta la proprietà che determina se la Forma è chiusa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Assegna un array di nodi Bexier.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Array di nodi Bezier |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


Le operazioni per la combinazione delle forme del percorso (operazioni booleane).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

