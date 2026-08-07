---
title: "StreamSource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta una sorgente di flusso."
type: docs
weight: 13
url: /it/java/com.aspose.psd.sources/streamsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public final class StreamSource extends Source
```

Rappresenta una sorgente di flusso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StreamSource()](#StreamSource--) | Inizializza una nuova istanza della classe  StreamSource  con stream Null. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Inizializza una nuova istanza della classe [StreamSource](../../com.aspose.psd.sources/streamsource). |
| [StreamSource(OutputStream destStream)](#StreamSource-java.io.OutputStream-) | Inizializza una nuova istanza della classe [StreamSource](../../com.aspose.psd.sources/streamsource). |
| [StreamSource(OutputStream destStream, boolean disposeStream)](#StreamSource-java.io.OutputStream-boolean-) |  |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) |  |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Inizializza una nuova istanza della classe [StreamSource](../../com.aspose.psd.sources/streamsource). |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposeStream()](#getDisposeStream--) | Ottiene un valore che indica se lo stream deve essere eliminato ogni volta che il contenitore viene eliminato. |
| [getStream()](#getStream--) |  |
| [getStreamContainer()](#getStreamContainer--) | Ottiene il contenitore dello stream. |
| [getStream_internalized()](#getStream-internalized--) | Ottiene lo stream. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setStream(InputStream value)](#setStream-java.io.InputStream-) |  |
| [setStream_internalized(System.IO.Stream value)](#setStream-internalized-com.aspose.ms.System.IO.Stream-) | Ottiene lo stream. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Inizializza una nuova istanza della  StreamSource  classe con stream Null. Questo costruttore consente di creare nuove immagini senza stream di input, immagini memorizzate solo in memoria.

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Inizializza una nuova istanza della classe [StreamSource](../../com.aspose.psd.sources/streamsource).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Lo stream da aprire. |

### StreamSource(OutputStream destStream) {#StreamSource-java.io.OutputStream-}
```
public StreamSource(OutputStream destStream)
```


Inizializza una nuova istanza della classe [StreamSource](../../com.aspose.psd.sources/streamsource).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destStream | java.io.OutputStream | un flusso di destinazione (ad es. java.io.ByteArrayOutputStream) |

### StreamSource(OutputStream destStream, boolean disposeStream) {#StreamSource-java.io.OutputStream-boolean-}
```
public StreamSource(OutputStream destStream, boolean disposeStream)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destStream | java.io.OutputStream |  |
| disposeStream | boolean |  |

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Inizializza una nuova istanza della classe [StreamSource](../../com.aspose.psd.sources/streamsource).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Lo stream da aprire. |
| disposeStream | boolean | se impostato su  true  il flusso verrà eliminato. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static StreamSource create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### create_internalized(System.IO.Stream stream, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-boolean-}
```
public static StreamSource create_internalized(System.IO.Stream stream, boolean disposeStream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
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
### getDisposeStream() {#getDisposeStream--}
```
public final boolean getDisposeStream()
```


Ottiene un valore che indica se lo stream deve essere eliminato ogni volta che il contenitore viene eliminato.

Valore:  true  se il flusso deve essere eliminato; altrimenti,  false .

**Returns:**
boolean
### getStream() {#getStream--}
```
public final System.IO.Stream getStream()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Ottiene il contenitore dello stream.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

--------------------

Usare con cautela. Sarà necessario eliminare il contenitore del flusso dopo il recupero.
### getStream_internalized() {#getStream-internalized--}
```
public final InputStream getStream_internalized()
```


Ottiene lo stream.

Valore: Il flusso di origine.

**Returns:**
java.io.InputStream
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




### setStream(InputStream value) {#setStream-java.io.InputStream-}
```
public final void setStream(InputStream value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.io.InputStream |  |

### setStream_internalized(System.IO.Stream value) {#setStream-internalized-com.aspose.ms.System.IO.Stream-}
```
public final void setStream_internalized(System.IO.Stream value)
```


Ottiene lo stream.

Valore: Il flusso di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.ms.System.IO.Stream |  |

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

