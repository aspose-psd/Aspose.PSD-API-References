---
title: "PathShape"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La figura dai nodi della curva Bezier."
type: docs
weight: 16
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

La figura dai nodi della curva Bezier.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PathShape()](#PathShape--) | Inizializza una nuova istanza della classe [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape). |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Inizializza una nuova istanza della classe [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | Ottiene l'array di nodi Bezier. |
| [getPathOperations()](#getPathOperations--) | Ottiene o imposta le operazioni di percorso (operazioni booleane). |
| [getShapeIndex()](#getShapeIndex--) | Ottiene o imposta l'indice della forma di percorso corrente nel livello. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Ottiene o imposta un valore che indica se questa istanza è chiusa. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | Ottiene o imposta un valore che indica se questa istanza è chiusa. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Assegna un array di nodi Bezier. |
| [setPathOperations(int value)](#setPathOperations-int-) | Ottiene o imposta le operazioni di percorso (operazioni booleane). |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Ottiene o imposta l'indice della forma di percorso corrente nel livello. |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | Crea i record  VectorPathRecord  basati su questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


Inizializza una nuova istanza della classe [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape).

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


Inizializza una nuova istanza della classe [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | Il record di lunghezza. |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | I record dei nodi Bezier. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItems() {#getItems--}
```
public final BezierKnotRecord[] getItems()
```


Ottiene l'array di nodi Bezier.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Array di BezierKnotRecord
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Ottiene o imposta le operazioni di percorso (operazioni booleane).

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Ottiene o imposta l'indice della forma di percorso corrente nel livello.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Ottiene o imposta un valore che indica se questa istanza è chiusa.

Valore:  true  se questa istanza è chiusa; altrimenti,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è chiusa.

Valore:  true  se questa istanza è chiusa; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


Assegna un array di nodi Bezier.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Array di nodi Bezier |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Ottiene o imposta le operazioni di percorso (operazioni booleane).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Ottiene o imposta l'indice della forma di percorso corrente nel livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toVectorPathRecords() {#toVectorPathRecords--}
```
public final System.Collections.Generic.IGenericEnumerable<VectorPathRecord> toVectorPathRecords()
```


Crea i record  VectorPathRecord  basati su questa istanza.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - Restituisce un  LengthRecord  e  BezierKnotRecord  per ogni punto in questa istanza.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

