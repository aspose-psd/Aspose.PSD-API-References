---
title: "CurvesDiscreteManager"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Manager für Curves Adjustment Layer, der die Pixelkarte manipuliert"
type: docs
weight: 25
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Manager für die Kurven‑Einstellungsebene, der die Pixelkarte manipuliert
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Initialisiert eine neue Instanz der [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Liest die Bytes für die Ressource. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Ermittelt die Karte für den Verarbeitungsfilter |
| [getMaxChannelCount()](#getMaxChannelCount--) | Liest die maximale Kanalanzahl. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Liest den Wert an Position. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Lädt Daten aus Bytes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Setzt den Standardwert an Position. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Setzt den Wert an Position. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Setzt den Wert des gesamten Kanals. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Initialisiert eine neue Instanz der [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxChannelCount | int | Die maximale Kanalanzahl. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Liest die Bytes für die Ressource.

**Returns:**
byte[] - Bytes zum Erstellen von CurvResource
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


Ermittelt die Karte für den Verarbeitungsfilter

**Returns:**
byte[][] - Transformationskarte
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Liest die maximale Kanalanzahl.

Wert: Die maximale Kanalanzahl.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Liest den Wert an Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| channelIndex | int | Index des Kanals. |
| position | byte | Die Position. |

**Returns:**
byte - Wert der Kurve an ihrer Position
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


Lädt Daten aus Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bytes | byte[] | Die Bytes. |

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


Setzt den Standardwert an Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| channelIndex | int | Index des Kanals. |
| position | byte | Die Position. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Setzt den Wert an Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| channelIndex | int | Index des Kanals. |
| position | byte | Die Position. |
| Wert | byte | Der Wert. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Setzt den Wert des gesamten Kanals.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| channelIndex | int | Index des Kanals. |
| channelValue | byte[] | Der Kanalwert. |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

