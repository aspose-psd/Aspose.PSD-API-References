---
title: "LengthRecord"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Unterpfad‑Längen‑Datensatz‑Klasse"
type: docs
weight: 13
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

Unterpfad‑Längen‑Datensatz‑Klasse
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | Initialisiert eine neue Instanz der [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) Klasse. |
| [LengthRecord()](#LengthRecord--) | Initialisiert eine neue Instanz der [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | Liest oder setzt die Anzahl der Bezier‑Knoten‑Datensätze. |
| [getClass()](#getClass--) |  |
| [getLength_internalized()](#getLength-internalized--) | Liefert die Länge. |
| [getPathOperations()](#getPathOperations--) | Liest oder setzt die Pfadoperationen. |
| [getRecordCount()](#getRecordCount--) | Liest oder setzt die Datensatzanzahl. |
| [getShapeIndex()](#getShapeIndex--) | Liefert oder setzt den Index der aktuellen Pfadform im Layer. |
| [getSourceData_internalized()](#getSourceData-internalized--) | Rufe die ursprünglichen Quelldaten‑Bytes ab. |
| [getType()](#getType--) | Liefert den Typ. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Liefert oder setzt einen Wert, der angibt, ob diese Instanz geschlossen ist. |
| [isOpen()](#isOpen--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz geöffnet ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | Liest oder setzt die Anzahl der Bezier‑Knoten‑Datensätze. |
| [setClosed(boolean value)](#setClosed-boolean-) | Liefert oder setzt einen Wert, der angibt, ob diese Instanz geschlossen ist. |
| [setOpen(boolean value)](#setOpen-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz geöffnet ist. |
| [setPathOperations(int value)](#setPathOperations-int-) | Liest oder setzt die Pfadoperationen. |
| [setRecordCount(int value)](#setRecordCount-int-) | Liest oder setzt die Datensatzanzahl. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Liefert oder setzt den Index der aktuellen Pfadform im Layer. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


Initialisiert eine neue Instanz der [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Aufzeichnungsdaten. |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


Initialisiert eine neue Instanz der [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) Klasse.

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
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


Liest oder setzt die Anzahl der Bezier‑Knoten‑Datensätze.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength_internalized() {#getLength-internalized--}
```
public final int getLength_internalized()
```


Liefert die Länge.

Wert: Die Länge.

**Returns:**
int
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Liest oder setzt die Pfadoperationen.

**Returns:**
int
### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


Liest oder setzt die Datensatzanzahl.

Wert: Die Datensatzanzahl.

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Liefert oder setzt den Index der aktuellen Pfadform im Layer.

**Returns:**
int
### getSourceData_internalized() {#getSourceData-internalized--}
```
public final byte[] getSourceData_internalized()
```


Rufe die ursprünglichen Quelldaten‑Bytes ab.

**Returns:**
byte[] - Byte‑Array.
### getType() {#getType--}
```
public short getType()
```


Liefert den Typ.

Wert: Der Typ.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Liefert oder setzt einen Wert, der angibt, ob diese Instanz geschlossen ist.

Wert:  true  wenn diese Instanz geschlossen ist; andernfalls,  false .

**Returns:**
boolean
### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz geöffnet ist.

Wert:  true  wenn diese Instanz geöffnet ist; andernfalls  false .

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




### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


Liest oder setzt die Anzahl der Bezier‑Knoten‑Datensätze.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Liefert oder setzt einen Wert, der angibt, ob diese Instanz geschlossen ist.

Wert:  true  wenn diese Instanz geschlossen ist; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz geöffnet ist.

Wert:  true  wenn diese Instanz geöffnet ist; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Liest oder setzt die Pfadoperationen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


Liest oder setzt die Datensatzanzahl.

Wert: Die Datensatzanzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Liefert oder setzt den Index der aktuellen Pfadform im Layer.

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

