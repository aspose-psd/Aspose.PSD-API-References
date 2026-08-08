---
title: "IPathShape"
second_title: "Aspose.PSD för Java API-referens"
description: "Shape från knutarna i Bezier-kurvan."
type: docs
weight: 31
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

Shape från knutarna i Bezier-kurvan.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getItems()](#getItems--) | Hämtar en array av Bezier-knutar. |
| [getPathOperations()](#getPathOperations--) | Operationerna för att kombinera banformer (booleska operationer). |
| [isClosed()](#isClosed--) | Hämtar eller anger egenskap som bestämmer om Shape är sluten. |
| [setClosed(boolean value)](#setClosed-boolean-) | Hämtar eller anger egenskap som bestämmer om Shape är sluten. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Tilldelar en array av Bexier-knutar. |
| [setPathOperations(int value)](#setPathOperations-int-) | Operationerna för att kombinera banformer (booleska operationer). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Hämtar en array av Bezier-knutar.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Array av BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


Operationerna för att kombinera banformer (booleska operationer).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Hämtar eller anger egenskap som bestämmer om Shape är sluten.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Hämtar eller anger egenskap som bestämmer om Shape är sluten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Tilldelar en array av Bexier-knutar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Array av Bezier-knutar |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


Operationerna för att kombinera banformer (booleska operationer).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

