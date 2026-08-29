---
title: "CurvesDiscreteManager"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Beheerder voor Curves Adjustment Layer die de pixelkaart manipuleert"
type: docs
weight: 25
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Beheerder voor Curves-aanpassingslaag die de pixelkaart bewerkt
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Initialiseert een nieuw exemplaar van de [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Haalt de bytes voor de resource op. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Haalt de map op voor verwerkingsfilter |
| [getMaxChannelCount()](#getMaxChannelCount--) | Haalt het maximale kanaalaantal op. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Haalt de waarde op op positie. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Laadt gegevens van bytes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Stelt in op de standaardwaarde op positie. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Stelt de waarde in op positie. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Stelt de waarde van het volledige kanaal in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Initialiseert een nieuw exemplaar van de [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxChannelCount | int | Het maximale kanaalaantal. |

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
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Haalt de map op voor verwerkingsfilter

**Returns:**
byte[][] - Transformatietabel
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Haalt het maximale kanaalaantal op.

Waarde: Het maximale kanaalaantal.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Haalt de waarde op op positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelIndex | int | Index van het kanaal. |
| position | byte | De positie. |

**Returns:**
byte - Waarde van curve op basis van positie
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




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


Stelt in op de standaardwaarde op positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelIndex | int | Index van het kanaal. |
| position | byte | De positie. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Stelt de waarde in op positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelIndex | int | Index van het kanaal. |
| position | byte | De positie. |
| waarde | byte | De waarde. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Stelt de waarde van het volledige kanaal in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelIndex | int | Index van het kanaal. |
| channelValue | byte[] | De kanaalwaarde. |

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

