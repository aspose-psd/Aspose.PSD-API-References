---
title: "CurvesContinuousManager"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Manager für die Kurven‑Einstellungsebene, der Kurven manipuliert"
type: docs
weight: 24
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

Manager für die Kurven‑Einstellungsebene, der Kurven manipuliert
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | Initialisiert eine neue Instanz der [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | Fügt den Punkt der Kurve hinzu. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Liest die Bytes für die Ressource. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | Liest den Kurvenpunkt nach Index. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | Liest die Anzahl der Kurvenpunkte. |
| [getMap_internalized()](#getMap-internalized--) | Liest die Karte für den Verarbeitungsfilter. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Liest die maximale Kanalanzahl. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Lädt Daten aus Bytes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | Entfernt den Punkt der Kurve. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | Aktualisiert den Punkt der Kurve. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


Initialisiert eine neue Instanz der [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxChannelCount | int | Die maximale Kanalanzahl. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


Fügt den Punkt der Kurve hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| channelIndex | int | Index des Kanals. |
| x | byte | Der x-Standort. |
| y | byte | Der y-Standort. |

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
### getCurvePointByIndex(int channelIndex, int pointIndex) {#getCurvePointByIndex-int-int-}
```
public final Point getCurvePointByIndex(int channelIndex, int pointIndex)
```


Liest den Kurvenpunkt nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| channelIndex | int | Index des Kanals. |
| pointIndex | int | Index des Punktes. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


Liest die Anzahl der Kurvenpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| channelIndex | int | Index des Kanals. |

**Returns:**
int - Anzahl der Kurvenpunkte im Kanal
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Liest die Karte für den Verarbeitungsfilter.

**Returns:**
byte[][] - Karte für die Kanalverarbeitung.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Liest die maximale Kanalanzahl.

Wert: Die maximale Kanalanzahl.

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




### removeCurvePoint(int channelIndex, int pointIndex) {#removeCurvePoint-int-int-}
```
public final void removeCurvePoint(int channelIndex, int pointIndex)
```


Entfernt den Punkt der Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| channelIndex | int | Index des Kanals. |
| pointIndex | int | Index des Punktes. |

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


Aktualisiert den Punkt der Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| channelIndex | int | Index des Kanals. |
| pointIndex | int | Index des Punktes. |
| x | byte | Der x-Standort. |
| y | byte | Der y-Standort. |

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

