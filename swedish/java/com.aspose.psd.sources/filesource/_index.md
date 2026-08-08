---
title: "FileSource"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en filkälla som kan manipulera filer."
type: docs
weight: 12
url: /sv/java/com.aspose.psd.sources/filesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public abstract class FileSource extends Source
```

Representerar en filkälla som kan manipulera filer.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FileSource()](#FileSource--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getStreamContainer()](#getStreamContainer--) | Hämtar strömbehållaren. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Hämtar ett värde som indikerar om filen kommer att vara temporär. |
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
| Parameter | Typ | Beskrivning |
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


Hämtar strömbehållaren.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

Använd med försiktighet. Du måste avyttra strömbehållaren efter hämtning.
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


Hämtar ett värde som indikerar om filen kommer att vara temporär.

**Returns:**
boolesk -  true  om filen kommer att vara temporär; annars,  false .
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

