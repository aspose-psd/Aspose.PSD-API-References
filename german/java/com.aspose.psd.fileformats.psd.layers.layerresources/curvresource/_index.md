---
title: "CurvResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Klasse CurvResource."
type: docs
weight: 23
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class CurvResource extends AdjustmentLayerResource
```

Klasse CurvResource. Ressource der Kurven-Anpassungsebene 1 Byte - 0 wenn Kurven verwendet werden, 1 wenn Pixel auf der Karte verwendet werden, wenn 0 dann: 2 Bytes - Short. Standard ist 1 4 Bytes - Int. Nur das letzte Byte wird bitweise verwendet. Das erste Bit ist für 1 Kanal, das vierte Bit für 4 Kanäle, zum Beispiel 2 Bytes - Short-Punktanzahl 4 Bytes \* Anzahl der Punkte - Punkte der Kurve 2 Short: erste Position, zweite Höhe 4 Bytes - Wort \"Crv \" 2 Bytes - Short, Standard ist 4 für Kurven 4 Bytes - Int. Standard ist 1 4 Bytes - Punktanzahl 4 Bytes \* Punktanzahl - Punkte der Kurve 2 Short: erste Position, zweite Höhe 0-4 Bytes - Führend, um für Vierfachwerte gefaltet zu werden, wenn 1 dann: 2 Bytes - Short. Standard ist 1 4 Bytes - Int. Nur das letzte Byte wird verwendet. Ein Kanal ist in einem Bit. Das erste Bit ist für 1 Kanal, das vierte Bit für 4 Kanäle, zum Beispiel 256 \* Anzahl geänderter Kanäle - geordnete Werte des Kanals im Bereich 0 - 255 4 Bytes - Wort \"Crv \" 2 Bytes - Short. Standard ist 3 für Pixel auf der Karte 4 Bytes - Int Kanalanzahl (2 + 256) Bytes - Short 2 für Kanalindex, 256 ist geordnete Werte des Kanals im Bereich 0 - 255
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CurvResource(int maxChannelCount)](#CurvResource-int-) | Initialisiert eine neue Instanz der Klasse [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource). |
| [CurvResource(byte[] bytes)](#CurvResource-byte---) | Initialisiert eine neue Instanz der Klasse [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource). |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Die PSB‑Header‑Version |
| [PsbResourceSignature](#PsbResourceSignature) | Die PSB‑spezifische Ressourcen‑Signatur. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Die PSD‑Header‑Version |
| [ResourceSignature](#ResourceSignature) | Die allgemeine Ressourcen‑Signatur. |
| [TypeToolKey](#TypeToolKey) | Der Typ-Tool-Info-Schlüssel. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Die Venture-Lizenz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Überprüft das und setzt, ob die Ressource PSB-spezifisch ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveManager()](#getActiveManager--) | Ruft den aktiven Manager ab. |
| [getChannelData(int channelIndex)](#getChannelData-int-) | Ruft die Kanaldaten ab. |
| [getClass()](#getClass--) |  |
| [getCurveManager()](#getCurveManager--) | Ruft den Kurven-Manager ab. |
| [getData()](#getData--) | Liest oder setzt die Daten. |
| [getHeader_internalized()](#getHeader-internalized--) | Ermittelt oder legt den Header fest. |
| [getKey()](#getKey--) | Ermittelt den Schichtressourcen-Schlüssel. |
| [getLength()](#getLength--) | Ermittelt die Länge der Schichtressource in Bytes. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ermittelt die Präfixlänge. |
| [getPsdVersion()](#getPsdVersion--) | Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. |
| [getSignature()](#getSignature--) | Ermittelt die Signatur der Schichtressource. |
| [hashCode()](#hashCode--) |  |
| [isDataStoredDiscretely()](#isDataStoredDiscretely--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz diskret gespeicherte Daten enthält. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestimmt, ob die Ressource PSB-spezifisch ist. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Speichert die Ressource im angegebenen Stream-Container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Speichert den benutzerdefinierten Ressourcen-Header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Speichert die Header-Signatur, den Bezeichner und die Länge. |
| [setDataStoredDiscretely(boolean value)](#setDataStoredDiscretely-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz diskret gespeicherte Daten enthält. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ermittelt oder legt den Header fest. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvResource(int maxChannelCount) {#CurvResource-int-}
```
public CurvResource(int maxChannelCount)
```


Initialisiert eine neue Instanz der Klasse [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxChannelCount | int | Die maximale Kanalanzahl. |

### CurvResource(byte[] bytes) {#CurvResource-byte---}
```
public CurvResource(byte[] bytes)
```


Initialisiert eine neue Instanz der Klasse [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bytes | byte[] | Die Bytes. |

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Die PSB‑Header‑Version

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Die PSB‑spezifische Ressourcen‑Signatur.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Die PSD‑Header‑Version

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Die allgemeine Ressourcen‑Signatur.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Der Typ-Tool-Info-Schlüssel.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Die Venture-Lizenz.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Überprüft das und setzt, ob die Ressource PSB-spezifisch ist. Einige Ressourcen werden derzeit nicht erkannt, aber wir haben eine vollständige Liste von PSB-spezifischen Ressourcen, die ihr Verhalten beim Speichern ändern. Daher müssen wir dies zumindest in UnknownResource überprüfen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | int | Der Schlüssel. |

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
### getActiveManager() {#getActiveManager--}
```
public final CurvesManager getActiveManager()
```


Ruft den aktiven Manager ab.

**Returns:**
[CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) - Active manager
### getChannelData(int channelIndex) {#getChannelData-int-}
```
public final byte[] getChannelData(int channelIndex)
```


Ruft die Kanaldaten ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| channelIndex | int | Index des Kanals. |

**Returns:**
byte[] - Kanaldaten
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurveManager() {#getCurveManager--}
```
public final CurvesManager getCurveManager()
```


Ruft den Kurven-Manager ab.

**Returns:**
[CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) - [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) or [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager)
### getData() {#getData--}
```
public final byte[] getData()
```


Liest oder setzt die Daten.

Wert: Die Daten.

**Returns:**
byte[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


Ermittelt den Schichtressourcen-Schlüssel.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Ermittelt die Länge der Schichtressource in Bytes.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Ermittelt die Präfixlänge. Standardwert ist 12 für 8BIM-Ressourcen und 16 für 8B64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| psdVersion | int | Die PSD‑Version. |

**Returns:**
int - Die Präfixlänge.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ermittelt die Signatur der Schichtressource.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDataStoredDiscretely() {#isDataStoredDiscretely--}
```
public final boolean isDataStoredDiscretely()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz diskret gespeicherte Daten enthält.

Wert:  true  wenn diese Instanz diskret gespeicherte Daten enthält; andernfalls  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Bestimmt, ob die Ressource PSB-spezifisch ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | int | Der Ressourcen-Schlüssel. |

**Returns:**
boolean -  true  wenn die Ressource PSB-spezifisch ist; andernfalls  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist.

Wert:  true  wenn diese Instanz ressourcen-PSB-spezifisch ist; andernfalls  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert wird. |
| psdVersion | int | Die PSD‑Version. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Speichert den benutzerdefinierten Ressourcen-Header.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| Signatur | int | Die Signatur. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Speichert die Header-Signatur, den Bezeichner und die Länge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| Signatur | int | Die Signatur. |
| isLengthLong | boolean | wenn auf  true  gesetzt, ist die Länge lang. |

### setDataStoredDiscretely(boolean value) {#setDataStoredDiscretely-boolean-}
```
public final void setDataStoredDiscretely(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz diskret gespeicherte Daten enthält.

Wert:  true  wenn diese Instanz diskret gespeicherte Daten enthält; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### toString() {#toString--}
```
public String toString()
```


Gibt einen String zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein String, der diese Instanz darstellt.
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

