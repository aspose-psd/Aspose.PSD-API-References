---
title: "PathShape"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La figure à partir des nœuds de la courbe Bézier."
type: docs
weight: 16
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

La figure à partir des nœuds de la courbe Bézier.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PathShape()](#PathShape--) | Initialise une nouvelle instance de la classe [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape). |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Initialise une nouvelle instance de la classe [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | Obtient le tableau de nœuds Bézier. |
| [getPathOperations()](#getPathOperations--) | Obtient ou définit les opérations de chemin (opérations booléennes). |
| [getShapeIndex()](#getShapeIndex--) | Obtient ou définit l'index de la forme de chemin actuelle dans le calque. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Obtient ou définit une valeur indiquant si cette instance est fermée. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | Obtient ou définit une valeur indiquant si cette instance est fermée. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Assigne le tableau de nœuds Bézier. |
| [setPathOperations(int value)](#setPathOperations-int-) | Obtient ou définit les opérations de chemin (opérations booléennes). |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Obtient ou définit l'index de la forme de chemin actuelle dans le calque. |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | Crée les enregistrements  VectorPathRecord  basés sur cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


Initialise une nouvelle instance de la classe [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape).

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


Initialise une nouvelle instance de la classe [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | L'enregistrement de longueur. |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Les enregistrements de nœuds Bézier. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient le tableau de nœuds Bézier.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Tableau de BezierKnotRecord
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Obtient ou définit les opérations de chemin (opérations booléennes).

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Obtient ou définit l'index de la forme de chemin actuelle dans le calque.

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


Obtient ou définit une valeur indiquant si cette instance est fermée.

Valeur :  true  si cette instance est fermée ; sinon,  false .

**Returns:**
booléen
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


Obtient ou définit une valeur indiquant si cette instance est fermée.

Valeur :  true  si cette instance est fermée ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


Assigne le tableau de nœuds Bézier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Tableau de nœuds Bézier |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Obtient ou définit les opérations de chemin (opérations booléennes).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Obtient ou définit l'index de la forme de chemin actuelle dans le calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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


Crée les enregistrements  VectorPathRecord  basés sur cette instance.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - Renvoie un  LengthRecord  et un  BezierKnotRecord  pour chaque point de cette instance.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

