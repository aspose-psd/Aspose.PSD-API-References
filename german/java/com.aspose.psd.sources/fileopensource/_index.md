---
title: "FileOpenSource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt eine Dateiquelle zum Öffnen dar."
type: docs
weight: 11
url: /de/java/com.aspose.psd.sources/fileopensource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source), [com.aspose.psd.sources.FileSource](../../com.aspose.psd.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Stellt eine Dateiquelle zum Öffnen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Initialisiert eine neue Instanz der  FileOpenSource  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | Gibt den zu öffnenden Dateipfad zurück. |
| [getStreamContainer()](#getStreamContainer--) | Gibt den Stream‑Container zurück. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Gibt einen Wert zurück, der angibt, ob die Datei temporär sein wird. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Initialisiert eine neue Instanz der  FileOpenSource  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der zu öffnende Dateipfad. |

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
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Gibt den zu öffnenden Dateipfad zurück.

Wert: Der zu öffnende Dateipfad.

**Returns:**
java.lang.String
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Gibt den Stream‑Container zurück.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

Vorsichtig verwenden. Der Stream‑Container muss nach dem Abrufen verworfen werden.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Gibt einen Wert zurück, der angibt, ob die Datei temporär sein wird.

Wert:  true  wenn die Datei temporär sein wird; andernfalls  false .

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

