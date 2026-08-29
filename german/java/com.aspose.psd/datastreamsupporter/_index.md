---
title: "DataStreamSupporter"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Datenstrom-Container."
type: docs
weight: 38
url: /de/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Der Datenstrom-Container.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Tritt auf, wenn das Bild geladen oder gespeichert wurde |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Tritt auf, wenn ein Guthaben verwendet wurde |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [cacheData()](#cacheData--) | Puffert die Daten und stellt sicher, dass keine zusätzlichen Daten aus dem zugrunde liegenden DataStreamSupporter.DataStreamContainer geladen werden. |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Liest den Datenstrom des Objekts. |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Liest den Dateipfad des Quellbildes, falls es existiert. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Liest einen Wert, der angibt, ob das Objekt eine Speicheroptimierungsstrategie verwendet |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Gibt einen Wert zurück, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Speichert die Daten des Objekts im aktuellen DataStreamSupporter. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Speichert die Objektdaten in den angegebenen Stream. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Speichert die Objektdaten in den angegebenen Stream. |
| [save(String filePath)](#save-java.lang.String-) | Speichert die Objektdaten am angegebenen Speicherort. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Speichert die Objektdaten am angegebenen Speicherort. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Setzt den Datenstream des Objekts. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Setzt einen Wert, der angibt, ob [ignore after save]. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Tritt auf, wenn das Bild geladen oder gespeichert wurde

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Tritt auf, wenn ein Guthaben verwendet wurde

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Puffert die Daten und stellt sicher, dass keine zusätzlichen Daten aus dem zugrunde liegenden DataStreamSupporter.DataStreamContainer geladen werden.

### close() {#close--}
```
public void close()
```


Implementiert das Closable-Interface und kann seit JDK 1.7 in der try-with-resources-Anweisung verwendet werden. Diese Methode ruft einfach die dispose-Methode auf.

### dispose() {#dispose--}
```
public final void dispose()
```


Gibt die aktuelle Instanz frei.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Liest den Datenstrom des Objekts.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde.

**Returns:**
boolean -  true  wenn freigegeben; andernfalls,  false .
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Ruft den Dateipfad des Quellbildes ab, falls es existiert. Gibt einen leeren String zurück, wenn der Quellpfad nicht gefunden werden kann.

**Returns:**
java.lang.String - Der Dateipfad des Quellbildes.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Liest einen Wert, der angibt, ob das Objekt eine Speicheroptimierungsstrategie verwendet

Value:  true  wenn das Objekt eine Speicheroptimierungsstrategie verwendet; andernfalls,  false .

**Returns:**
boolean - ein Wert, der angibt, ob das Objekt eine Speicheroptimierungsstrategie verwendet
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Gibt einen Wert zurück, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.

**Returns:**
boolean – ein Wert, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


Speichert die Daten des Objekts im aktuellen DataStreamSupporter.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Speichert die Objektdaten in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Stream, in dem die Objektdaten gespeichert werden. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Speichert die Objektdaten in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Der Stream, in dem die Objektdaten gespeichert werden. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Speichert die Objektdaten am angegebenen Speicherort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Daten des Objekts gespeichert werden sollen. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Speichert die Objektdaten am angegebenen Speicherort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Daten des Objekts gespeichert werden sollen. |
| Überschreiben | boolean | Wenn auf true gesetzt, wird der Dateiinhalt überschrieben, andernfalls wird angehängt. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Setzt den Datenstream des Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Datenstrom des Objekts. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Setzt einen Wert, der angibt, ob [ignore after save].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true  wenn [ignore after save]; andernfalls,  false . |

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

