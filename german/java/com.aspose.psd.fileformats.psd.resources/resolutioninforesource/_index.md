---
title: "ResolutionInfoResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Auflösungsinfo-Ressource"
type: docs
weight: 33
url: /de/java/com.aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class ResolutionInfoResource extends ResourceBlock
```

Die Auflösungsinfo-Ressource
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ResolutionInfoResource()](#ResolutionInfoResource--) | Initialisiert eine neue Instanz der Klasse [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource). |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Die Ressourcensignatur von ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Die reguläre Photoshop‑Ressourcensignatur. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Liest die Größe der Ressourcendaten in Bytes. |
| [getHDpi()](#getHDpi--) | Horizontaler DPI. |
| [getHResDisplayUnit()](#getHResDisplayUnit--) | Anzeigeeinheiten für die horizontale Auflösung. |
| [getHeightDisplayUnit()](#getHeightDisplayUnit--) | Liest oder setzt die Anzeigeeinheit für die Höhe. |
| [getID()](#getID--) | Liest oder setzt die eindeutige Kennung für die Ressource. |
| [getMinimalVersion()](#getMinimalVersion--) | Ermittelt die minimal erforderliche PSD-Version. |
| [getName()](#getName--) | Liest oder setzt den Ressourcennamen. |
| [getSignature()](#getSignature--) | Ermittelt die Ressourcensignatur. |
| [getSize()](#getSize--) | Ermittelt die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten. |
| [getVDpi()](#getVDpi--) | Vertikaler DPI. |
| [getVResDisplayUnit()](#getVResDisplayUnit--) | Anzeigeeinheiten für die vertikale Auflösung. |
| [getWidthDisplayUnit()](#getWidthDisplayUnit--) | Liest oder setzt die Anzeigeeinheit für die Breite. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Speichert den Ressourcenblock in den angegebenen Stream. |
| [setHDpi(FixedPointDecimal value)](#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | Horizontaler DPI. |
| [setHResDisplayUnit(int value)](#setHResDisplayUnit-int-) | Anzeigeeinheiten für die horizontale Auflösung. |
| [setHeightDisplayUnit(int value)](#setHeightDisplayUnit-int-) | Liest oder setzt die Anzeigeeinheit für die Höhe. |
| [setID(short value)](#setID-short-) | Liest oder setzt die eindeutige Kennung für die Ressource. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Liest oder setzt die Ebenen- und Maskeninformationen. |
| [setName(String value)](#setName-java.lang.String-) | Liest oder setzt den Ressourcennamen. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Liest oder setzt den Zustand des Ressourcenblocks. |
| [setVDpi(FixedPointDecimal value)](#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | Vertikaler DPI. |
| [setVResDisplayUnit(int value)](#setVResDisplayUnit-int-) | Anzeigeeinheiten für die vertikale Auflösung. |
| [setWidthDisplayUnit(int value)](#setWidthDisplayUnit-int-) | Liest oder setzt die Anzeigeeinheit für die Breite. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validiert die Ressourcenwerte. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionInfoResource() {#ResolutionInfoResource--}
```
public ResolutionInfoResource()
```


Initialisiert eine neue Instanz der Klasse [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Die Ressourcensignatur von ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Die reguläre Photoshop‑Ressourcensignatur.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Liest die Größe der Ressourcendaten in Bytes.

Wert: Die Größe der Ressourcendaten.

**Returns:**
int
### getHDpi() {#getHDpi--}
```
public final FixedPointDecimal getHDpi()
```


Horizontaler DPI.

Wert: Der horizontale dpi.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getHResDisplayUnit() {#getHResDisplayUnit--}
```
public final int getHResDisplayUnit()
```


Anzeigeeinheiten für die horizontale Auflösung. Dies wirkt sich nur auf die Benutzeroberfläche aus; die Auflösung wird weiterhin in der PSD‑Datei als Pixel pro Zoll gespeichert.

Wert: Die Anzeigeeinheit für die horizontale Auflösung.

**Returns:**
int
### getHeightDisplayUnit() {#getHeightDisplayUnit--}
```
public final int getHeightDisplayUnit()
```


Liest oder setzt die Anzeigeeinheit für die Höhe.

Wert: Die Anzeigeeinheit für die Höhe.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Liest oder setzt die eindeutige Kennung für die Ressource.

Wert: Der eindeutige Bezeichner der Ressource.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Ermittelt die minimal erforderliche PSD-Version.

Wert: Die minimale PSD-Version.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Liest oder setzt den Ressourcennamen. Pascal-String, aufgefüllt, um die Größe gerade zu machen (ein Null-Name besteht aus zwei Bytes von 0).

Wert: Der Ressourcename.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Ermittelt die Ressourcensignatur. Sollte immer '8BIM' sein.

Wert: Die Ressourcensignatur.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Ermittelt die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten.

Wert: Die Größe des Ressourcenblocks.

**Returns:**
int
### getVDpi() {#getVDpi--}
```
public final FixedPointDecimal getVDpi()
```


Vertikaler DPI.

Wert: Der vertikale dpi.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getVResDisplayUnit() {#getVResDisplayUnit--}
```
public final int getVResDisplayUnit()
```


Anzeigeeinheiten für die vertikale Auflösung.

Wert: Die Anzeigeeinheit für die vertikale Auflösung.

**Returns:**
int
### getWidthDisplayUnit() {#getWidthDisplayUnit--}
```
public final int getWidthDisplayUnit()
```


Liest oder setzt die Anzeigeeinheit für die Breite.

Wert: Die Anzeigeeinheit für die Breite.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Speichert den Ressourcenblock in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream, in den der Ressourcenblock gespeichert wird. |

### setHDpi(FixedPointDecimal value) {#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setHDpi(FixedPointDecimal value)
```


Horizontaler DPI.

Wert: Der horizontale dpi.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setHResDisplayUnit(int value) {#setHResDisplayUnit-int-}
```
public final void setHResDisplayUnit(int value)
```


Anzeigeeinheiten für die horizontale Auflösung. Dies wirkt sich nur auf die Benutzeroberfläche aus; die Auflösung wird weiterhin in der PSD‑Datei als Pixel pro Zoll gespeichert.

Wert: Die Anzeigeeinheit für die horizontale Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setHeightDisplayUnit(int value) {#setHeightDisplayUnit-int-}
```
public final void setHeightDisplayUnit(int value)
```


Liest oder setzt die Anzeigeeinheit für die Höhe.

Wert: Die Anzeigeeinheit für die Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Liest oder setzt die eindeutige Kennung für die Ressource.

Wert: Der eindeutige Bezeichner der Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Liest oder setzt die Ebenen- und Maskeninformationen.

Wert: Die Ebenen- und Maskeninformationen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Liest oder setzt den Ressourcennamen. Pascal-String, aufgefüllt, um die Größe gerade zu machen (ein Null-Name besteht aus zwei Bytes von 0).

Wert: Der Ressourcename.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Signatur | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Liest oder setzt den Zustand des Ressourcenblocks.

Wert: Der Zustand des Ressourcenblocks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVDpi(FixedPointDecimal value) {#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setVDpi(FixedPointDecimal value)
```


Vertikaler DPI.

Wert: Der vertikale dpi.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setVResDisplayUnit(int value) {#setVResDisplayUnit-int-}
```
public final void setVResDisplayUnit(int value)
```


Anzeigeeinheiten für die vertikale Auflösung.

Wert: Die Anzeigeeinheit für die vertikale Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWidthDisplayUnit(int value) {#setWidthDisplayUnit-int-}
```
public final void setWidthDisplayUnit(int value)
```


Liest oder setzt die Anzeigeeinheit für die Breite.

Wert: Die Anzeigeeinheit für die Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Validiert die Ressourcenwerte.

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

