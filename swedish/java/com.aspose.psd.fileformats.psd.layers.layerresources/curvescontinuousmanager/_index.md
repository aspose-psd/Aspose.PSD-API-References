---
title: "CurvesContinuousManager"
second_title: "Aspose.PSD för Java API-referens"
description: "Manager för Curves Adjustment Layer som manipulerar kurvor"
type: docs
weight: 24
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

Manager för Curves Adjustment Layer som manipulerar kurvor
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | Initierar en ny instans av klassen [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) class. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | Lägger till en punkt på kurvan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Hämtar byte för resursen. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | Hämtar kurvpunkten efter index. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | Hämtar antalet kurvpunkter. |
| [getMap_internalized()](#getMap-internalized--) | Hämtar kartan för bearbetningsfilter. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Hämtar det maximala kanalantalet. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Läser in data från byte. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | Tar bort en punkt på kurvan. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | Uppdaterar en punkt på kurvan. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


Initierar en ny instans av klassen [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) class.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxChannelCount | int | Det maximala kanalantalet. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


Lägger till en punkt på kurvan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelIndex | int | Index för kanalen. |
| x | byte | x‑platsen. |
| y | byte | y‑platsen. |

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
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Hämtar byte för resursen.

**Returns:**
byte[] - Byte för att komponera CurvResource
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


Hämtar kurvpunkten efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelIndex | int | Index för kanalen. |
| pointIndex | int | Index för punkten. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


Hämtar antalet kurvpunkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelIndex | int | Index för kanalen. |

**Returns:**
int - Antal kurvpunkter i kanal
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Hämtar kartan för bearbetningsfilter.

**Returns:**
byte[][] - Karta för kanalbehandling.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Hämtar det maximala kanalantalet.

Värde: Det maximala kanalantalet.

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


Läser in data från byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | byte[] | Byte. |

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


Tar bort en punkt på kurvan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelIndex | int | Index för kanalen. |
| pointIndex | int | Index för punkten. |

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


Uppdaterar en punkt på kurvan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelIndex | int | Index för kanalen. |
| pointIndex | int | Index för punkten. |
| x | byte | x‑platsen. |
| y | byte | y‑platsen. |

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

