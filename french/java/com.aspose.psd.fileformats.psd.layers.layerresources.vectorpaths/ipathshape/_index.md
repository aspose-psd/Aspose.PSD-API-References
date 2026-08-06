---
title: "IPathShape"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La Shape des nœuds de la courbe Bézier."
type: docs
weight: 31
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

La Shape des nœuds de la courbe Bézier.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getItems()](#getItems--) | Obtient le tableau de nœuds Bézier. |
| [getPathOperations()](#getPathOperations--) | Les opérations de combinaison des formes de chemin (opérations booléennes). |
| [isClosed()](#isClosed--) | Obtient ou définit la propriété qui détermine si la forme est fermée. |
| [setClosed(boolean value)](#setClosed-boolean-) | Obtient ou définit la propriété qui détermine si la forme est fermée. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Assigne un tableau de nœuds Bexier. |
| [setPathOperations(int value)](#setPathOperations-int-) | Les opérations de combinaison des formes de chemin (opérations booléennes). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Obtient le tableau de nœuds Bézier.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Tableau de BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


Les opérations de combinaison des formes de chemin (opérations booléennes).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Obtient ou définit la propriété qui détermine si la forme est fermée.

**Returns:**
booléen
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Obtient ou définit la propriété qui détermine si la forme est fermée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Assigne un tableau de nœuds Bexier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Tableau de nœuds Bézier |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


Les opérations de combinaison des formes de chemin (opérations booléennes).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

