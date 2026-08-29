---
title: "VectorPathData"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Klasse zur Arbeit mit einem Vektorpfad."
type: docs
weight: 18
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

Die Klasse zur Arbeit mit einem Vektorpfad.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | Initialisiert eine neue Instanz der Klasse [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
| [VectorPathData()](#VectorPathData--) | Initialisiert eine neue Instanz der Klasse [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | Die Größe der allgemeinen Informationen wie Version und Flags. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | Liefert als Byte-Array. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Liefert die Länge der Vektorpfaddaten in der Ressource in Bytes. |
| [getPaths()](#getPaths--) | Liest oder setzt die Pfad‑Datensätze. |
| [getVersion()](#getVersion--) | Liest oder setzt die Version. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz deaktiviert ist. |
| [isInverted()](#isInverted--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz invertiert ist. |
| [isNotLinked()](#isNotLinked--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz nicht verknüpft ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz deaktiviert ist. |
| [setInverted(boolean value)](#setInverted-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz invertiert ist. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz nicht verknüpft ist. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Liest oder setzt die Pfad‑Datensätze. |
| [setVersion(int value)](#setVersion-int-) | Liest oder setzt die Version. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


Initialisiert eine neue Instanz der Klasse [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Ressourcendaten. |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


Initialisiert eine neue Instanz der Klasse [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


Die Größe der allgemeinen Informationen wie Version und Flags.

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


Liefert als Byte-Array.

**Returns:**
byte[] - Die Ressource als Byte-Array.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


Liefert die Länge der Vektorpfaddaten in der Ressource in Bytes.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Liest oder setzt die Pfad‑Datensätze.

Wert: Die Pfade.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
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

