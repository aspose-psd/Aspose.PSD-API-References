---
title: "FileSource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt eine Dateiquelle dar, die in der Lage ist, Dateien zu manipulieren."
type: docs
weight: 12
url: /de/java/com.aspose.psd.sources/filesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public abstract class FileSource extends Source
```

Stellt eine Dateiquelle dar, die in der Lage ist, Dateien zu manipulieren.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FileSource()](#FileSource--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getStreamContainer()](#getStreamContainer--) | Gibt den Stream‑Container zurück. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Gibt einen Wert zurück, der angibt, ob die Datei temporär sein wird. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileSource() {#FileSource--}
```
public FileSource()
```


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
### getStreamContainer() {#getStreamContainer--}
```
public abstract StreamContainer getStreamContainer()
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
public abstract boolean isTemporal()
```


Gibt einen Wert zurück, der angibt, ob die Datei temporär sein wird.

**Returns:**
boolescher Wert -  true  wenn die Datei temporär sein wird; andernfalls,  false .
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

