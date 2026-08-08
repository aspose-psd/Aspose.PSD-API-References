---
title: "PathShape"
second_title: "Aspose.PSD för Java API-referens"
description: "Figuren från knutarna i Bezier‑kurvan."
type: docs
weight: 16
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

Figuren från knutarna i Bezier‑kurvan.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PathShape()](#PathShape--) | Initierar en ny instans av klassen [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape). |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Initierar en ny instans av klassen [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | Hämtar en array av Bezier-knutar. |
| [getPathOperations()](#getPathOperations--) | Hämtar eller anger sökvägsoperationerna (booleska operationer). |
| [getShapeIndex()](#getShapeIndex--) | Hämtar eller anger indexet för den aktuella sökvägsformen i lagret. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Hämtar eller anger ett värde som indikerar om detta objekt är stängt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekt är stängt. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Tilldelar en array av Bezier-knutar. |
| [setPathOperations(int value)](#setPathOperations-int-) | Hämtar eller anger sökvägsoperationerna (booleska operationer). |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Hämtar eller anger indexet för den aktuella sökvägsformen i lagret. |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | Skapar  VectorPathRecord  -poster baserat på detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


Initierar en ny instans av klassen [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape).

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


Initierar en ny instans av klassen [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | Längdposten. |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezier-knutsposterna. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar en array av Bezier-knutar.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Array av BezierKnotRecord
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Hämtar eller anger sökvägsoperationerna (booleska operationer).

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Hämtar eller anger indexet för den aktuella sökvägsformen i lagret.

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


Hämtar eller anger ett värde som indikerar om detta objekt är stängt.

Värde:  true  om detta objekt är stängt; annars  false .

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


Hämtar eller anger ett värde som indikerar om detta objekt är stängt.

Värde:  true  om detta objekt är stängt; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


Tilldelar en array av Bezier-knutar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Array av Bezier-knutar |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Hämtar eller anger sökvägsoperationerna (booleska operationer).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Hämtar eller anger indexet för den aktuella sökvägsformen i lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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


Skapar  VectorPathRecord  -poster baserat på detta objekt.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - Returnerar en  LengthRecord  och  BezierKnotRecord  för varje punkt i detta objekt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

