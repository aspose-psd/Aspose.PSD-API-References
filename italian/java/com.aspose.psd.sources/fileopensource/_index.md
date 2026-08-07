---
title: "FileOpenSource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta una sorgente file per l'apertura."
type: docs
weight: 11
url: /it/java/com.aspose.psd.sources/fileopensource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source), [com.aspose.psd.sources.FileSource](../../com.aspose.psd.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Rappresenta una sorgente file per l'apertura.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Inizializza una nuova istanza della classe  FileOpenSource . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | Ottiene il percorso del file da aprire. |
| [getStreamContainer()](#getStreamContainer--) | Ottiene il contenitore dello stream. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Ottiene un valore che indica se il file sarà temporaneo. |
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


Inizializza una nuova istanza della classe  FileOpenSource .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file da aprire. |

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
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Ottiene il percorso del file da aprire.

Valore: Il percorso del file da aprire.

**Returns:**
java.lang.String
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
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
public boolean isTemporal()
```


Ottiene un valore che indica se il file sarà temporaneo.

Valore:  true  se il file sarà temporaneo; altrimenti,  false .

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

