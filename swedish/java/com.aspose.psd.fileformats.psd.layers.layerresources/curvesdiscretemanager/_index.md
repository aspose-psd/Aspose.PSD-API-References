---
title: "CurvesDiscreteManager"
second_title: "Aspose.PSD för Java API-referens"
description: "Manager för Curves Adjustment Layer som manipulerar pixelkartan"
type: docs
weight: 25
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Manager för Curves Adjustment Layer som manipulerar pixelkartan
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Initierar en ny instans av klassen [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Hämtar byte för resursen. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Hämtar kartan för bearbetningsfilter. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Hämtar det maximala kanalantalet. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Hämtar värdet på positionen. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Läser in data från byte. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Sätter till standardvärde på positionen. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Sätter värdet på positionen. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Sätter värdet för hela kanalen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Initierar en ny instans av klassen [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxChannelCount | int | Det maximala kanalantalet. |

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
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Hämtar kartan för bearbetningsfilter.

**Returns:**
byte[][] - Transformationskarta
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Hämtar det maximala kanalantalet.

Värde: Det maximala kanalantalet.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Hämtar värdet på positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelIndex | int | Index för kanalen. |
| position | byte | Positionen. |

**Returns:**
byte - Värde på kurva efter dess position
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




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


Sätter till standardvärde på positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelIndex | int | Index för kanalen. |
| position | byte | Positionen. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Sätter värdet på positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelIndex | int | Index för kanalen. |
| position | byte | Positionen. |
| värde | byte | Värdet. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Sätter värdet för hela kanalen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelIndex | int | Index för kanalen. |
| channelValue | byte[] | Kanalvärdet. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

