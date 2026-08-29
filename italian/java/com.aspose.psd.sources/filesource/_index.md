---
title: "FileSource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta una sorgente di file in grado di manipolare i file."
type: docs
weight: 12
url: /it/java/com.aspose.psd.sources/filesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public abstract class FileSource extends Source
```

Rappresenta una sorgente di file in grado di manipolare i file.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileSource()](#FileSource--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getStreamContainer()](#getStreamContainer--) | Ottiene il contenitore dello stream. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Ottiene un valore che indica se il file sarà temporaneo. |
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
| Parametro | Tipo | Descrizione |
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


Ottiene il contenitore dello stream.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

Usare con cautela. Sarà necessario eliminare il contenitore del flusso dopo il recupero.
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


Ottiene un valore che indica se il file sarà temporaneo.

**Returns:**
boolean -  true  se il file sarà temporaneo; altrimenti,  false .
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

