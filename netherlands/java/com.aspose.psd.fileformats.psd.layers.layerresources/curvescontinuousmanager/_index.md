---
title: "CurvesContinuousManager"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Beheerder voor Curves-aanpassingslaag die curven bewerkt"
type: docs
weight: 24
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

Beheerder voor Curves-aanpassingslaag die curven bewerkt
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | Initialiseert een nieuw exemplaar van de [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | Voegt het punt van de curve toe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Haalt de bytes voor de resource op. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | Haalt het curvepunt op via index. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | Haalt het aantal curvepunten op. |
| [getMap_internalized()](#getMap-internalized--) | Haalt de kaart voor verwerkingsfilter op. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Haalt het maximale kanaalaantal op. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Laadt gegevens van bytes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | Verwijdert het punt van de curve. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | Werkt het punt van de curve bij. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


Initialiseert een nieuw exemplaar van de [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxChannelCount | int | Het maximale kanaalaantal. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


Voegt het punt van de curve toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelIndex | int | Index van het kanaal. |
| x | byte | De x-locatie. |
| y | byte | De y-locatie. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Haalt de bytes voor de resource op.

**Returns:**
byte[] - Bytes om CurvResource samen te stellen
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurvePointByIndex(int channelIndex, int pointIndex) {#getCurvePointByIndex-int-int-}
```
public final Point getCurvePointByIndex(int channelIndex, int pointIndex)
```


Haalt het curvepunt op via index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelIndex | int | Index van het kanaal. |
| pointIndex | int | Index van het punt. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


Haalt het aantal curvepunten op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelIndex | int | Index van het kanaal. |

**Returns:**
int - Aantal curve-punten in kanaal
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Haalt de kaart voor verwerkingsfilter op.

**Returns:**
byte[][] - Kaart voor kanaalverwerking.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Haalt het maximale kanaalaantal op.

Waarde: Het maximale kanaalaantal.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadFromBytes_internalized(byte[] bytes) {#loadFromBytes-internalized-byte---}
```
public void loadFromBytes_internalized(byte[] bytes)
```


Laadt gegevens van bytes.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | byte[] | De bytes. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeCurvePoint(int channelIndex, int pointIndex) {#removeCurvePoint-int-int-}
```
public final void removeCurvePoint(int channelIndex, int pointIndex)
```


Verwijdert het punt van de curve.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelIndex | int | Index van het kanaal. |
| pointIndex | int | Index van het punt. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y) {#updateCurvePoint-int-int-byte-byte-}
```
public final void updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)
```


Werkt het punt van de curve bij.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelIndex | int | Index van het kanaal. |
| pointIndex | int | Index van het punt. |
| x | byte | De x-locatie. |
| y | byte | De y-locatie. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

