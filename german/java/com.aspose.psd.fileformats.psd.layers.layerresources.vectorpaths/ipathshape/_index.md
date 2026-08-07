---
title: "IPathShape"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Shape aus den Knoten der Bézier-Kurve."
type: docs
weight: 31
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

Die Shape aus den Knoten der Bézier-Kurve.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getItems()](#getItems--) | Liefert ein Array von Bezier-Knoten. |
| [getPathOperations()](#getPathOperations--) | Die Vorgänge zum Kombinieren von Pfadformen (Boolesche Operationen). |
| [isClosed()](#isClosed--) | Liest oder setzt die Eigenschaft, die bestimmt, ob die Form geschlossen ist. |
| [setClosed(boolean value)](#setClosed-boolean-) | Liest oder setzt die Eigenschaft, die bestimmt, ob die Form geschlossen ist. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Weist ein Array von Bexier-Knoten zu. |
| [setPathOperations(int value)](#setPathOperations-int-) | Die Vorgänge zum Kombinieren von Pfadformen (Boolesche Operationen). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Liefert ein Array von Bezier-Knoten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Array von BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


Die Vorgänge zum Kombinieren von Pfadformen (Boolesche Operationen).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Liest oder setzt die Eigenschaft, die bestimmt, ob die Form geschlossen ist.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Liest oder setzt die Eigenschaft, die bestimmt, ob die Form geschlossen ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Weist ein Array von Bexier-Knoten zu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Array von Bezier-Knoten |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


Die Vorgänge zum Kombinieren von Pfadformen (Boolesche Operationen).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

