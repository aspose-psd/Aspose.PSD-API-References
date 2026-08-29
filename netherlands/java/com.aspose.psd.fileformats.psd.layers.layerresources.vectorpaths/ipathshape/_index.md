---
title: "IPathShape"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De Shape van de knooppunten van de Bezier-curve."
type: docs
weight: 31
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

De Shape van de knooppunten van de Bezier-curve.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getItems()](#getItems--) | Haalt array van Bezier-knopen op. |
| [getPathOperations()](#getPathOperations--) | De bewerkingen voor het combineren van padvormen (Boolean‑bewerkingen). |
| [isClosed()](#isClosed--) | Haalt of stelt de eigenschap in die bepaalt of Shape gesloten is. |
| [setClosed(boolean value)](#setClosed-boolean-) | Haalt of stelt de eigenschap in die bepaalt of Shape gesloten is. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Wijst een array van Bexier-knopen toe. |
| [setPathOperations(int value)](#setPathOperations-int-) | De bewerkingen voor het combineren van padvormen (Boolean‑bewerkingen). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Haalt array van Bezier-knopen op.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Array van BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


De bewerkingen voor het combineren van padvormen (Boolean‑bewerkingen).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Haalt of stelt de eigenschap in die bepaalt of Shape gesloten is.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Haalt of stelt de eigenschap in die bepaalt of Shape gesloten is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Wijst een array van Bexier-knopen toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Array van Bezier-knooppunten |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


De bewerkingen voor het combineren van padvormen (Boolean‑bewerkingen).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

