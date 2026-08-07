---
title: "IccProfileResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt die ICC‑Profil‑Ressource dar."
type: docs
weight: 23
url: /de/java/com.aspose.psd.fileformats.psd.resources/iccprofileresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class IccProfileResource extends ResourceBlock
```

Stellt die ICC‑Profil‑Ressource dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [IccProfileResource()](#IccProfileResource--) | Initialisiert eine neue Instanz der Klasse [IccProfileResource](../../com.aspose.psd.fileformats.psd.resources/iccprofileresource). |
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
| [getID()](#getID--) | Liest oder setzt die eindeutige Kennung für die Ressource. |
| [getIccProfile()](#getIccProfile--) | Liest oder setzt das ICC‑Profil. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getMinimalVersion()](#getMinimalVersion--) | Ermittelt die minimal erforderliche PSD-Version. |
| [getName()](#getName--) | Liest oder setzt den Ressourcennamen. |
| [getSignature()](#getSignature--) | Ermittelt die Ressourcensignatur. |
| [getSize()](#getSize--) | Ermittelt die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Speichert den Ressourcenblock in den angegebenen Stream. |
| [setID(short value)](#setID-short-) | Liest oder setzt die eindeutige Kennung für die Ressource. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Liest oder setzt das ICC‑Profil. |
| [setIccProfile_internalized(System.IO.MemoryStream value)](#setIccProfile-internalized-com.aspose.ms.System.IO.MemoryStream-) |  |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Liest oder setzt die Ebenen- und Maskeninformationen. |
| [setName(String value)](#setName-java.lang.String-) | Liest oder setzt den Ressourcennamen. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Liest oder setzt den Zustand des Ressourcenblocks. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validiert die Ressourcenwerte. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IccProfileResource() {#IccProfileResource--}
```
public IccProfileResource()
```


Initialisiert eine neue Instanz der Klasse [IccProfileResource](../../com.aspose.psd.fileformats.psd.resources/iccprofileresource).

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
### getID() {#getID--}
```
public final short getID()
```


Liest oder setzt die eindeutige Kennung für die Ressource.

Wert: Der eindeutige Bezeichner der Ressource.

**Returns:**
short
### getIccProfile() {#getIccProfile--}
```
public final byte[] getIccProfile()
```


Liest oder setzt das ICC‑Profil.

Wert: Das ICC‑Profil.

**Returns:**
byte[]
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public final System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
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

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public final void setIccProfile(byte[] value)
```


Liest oder setzt das ICC‑Profil.

Wert: Das ICC‑Profil.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setIccProfile_internalized(System.IO.MemoryStream value) {#setIccProfile-internalized-com.aspose.ms.System.IO.MemoryStream-}
```
public final void setIccProfile_internalized(System.IO.MemoryStream value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.IO.MemoryStream |  |

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

