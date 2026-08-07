---
title: "WorkingPathResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Arbeits-Pfad-Ressource."
type: docs
weight: 43
url: /de/java/com.aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class WorkingPathResource extends ResourceBlock implements IVectorPathData
```

Arbeits-Pfad-Ressource.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WorkingPathResource(byte[] dataBytes)](#WorkingPathResource-byte---) | Initialisiert eine neue Instanz der Klasse [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource). |
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
| [getMinimalVersion()](#getMinimalVersion--) | Ermittelt die minimal erforderliche PSD-Version. |
| [getName()](#getName--) | Liest oder setzt den Ressourcennamen. |
| [getPaths()](#getPaths--) | Liest oder setzt die Pfad‑Datensätze. |
| [getSignature()](#getSignature--) | Ermittelt die Ressourcensignatur. |
| [getSize()](#getSize--) | Ermittelt die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten. |
| [getVersion()](#getVersion--) | Liest oder setzt die Version. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz deaktiviert ist. |
| [isInverted()](#isInverted--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz invertiert ist. |
| [isNotLinked()](#isNotLinked--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz nicht verknüpft ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Speichert den Ressourcenblock in den angegebenen Stream. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz deaktiviert ist. |
| [setID(short value)](#setID-short-) | Liest oder setzt die eindeutige Kennung für die Ressource. |
| [setInverted(boolean value)](#setInverted-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz invertiert ist. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Liest oder setzt die Ebenen- und Maskeninformationen. |
| [setName(String value)](#setName-java.lang.String-) | Liest oder setzt den Ressourcennamen. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz nicht verknüpft ist. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Liest oder setzt die Pfad‑Datensätze. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Liest oder setzt den Zustand des Ressourcenblocks. |
| [setVersion(int value)](#setVersion-int-) | Liest oder setzt die Version. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validiert die Ressourcenwerte. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WorkingPathResource(byte[] dataBytes) {#WorkingPathResource-byte---}
```
public WorkingPathResource(byte[] dataBytes)
```


Initialisiert eine neue Instanz der Klasse [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataBytes | byte[] | Die Daten des Vektorpfads. |

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
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Liest oder setzt die Pfad‑Datensätze.

Wert: Die Pfade.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
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
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Liest oder setzt die Version.

Wert: Die Version.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz deaktiviert ist.

Wert:  true  wenn diese Instanz deaktiviert ist; andernfalls  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz invertiert ist.

Wert:  true  wenn diese Instanz invertiert ist; andernfalls  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz nicht verknüpft ist.

Wert:  true  wenn diese Instanz nicht verknüpft ist; andernfalls  false .

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Speichert den Ressourcenblock in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream, in den der Ressourcenblock gespeichert wird. |

### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz deaktiviert ist.

Wert:  true  wenn diese Instanz deaktiviert ist; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz invertiert ist.

Wert:  true  wenn diese Instanz invertiert ist; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz nicht verknüpft ist.

Wert:  true  wenn diese Instanz nicht verknüpft ist; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Liest oder setzt die Pfad‑Datensätze.

Wert: Die Pfade.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

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

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Liest oder setzt die Version.

Wert: Die Version.

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

