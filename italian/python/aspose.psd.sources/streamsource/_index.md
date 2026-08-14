---
title: "Classe StreamSource"
type: docs
weight: 40
url: /it/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | Inizializza una nuova istanza della classe [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Inizializza una nuova istanza della classe [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Ottiene un valore che indica se lo stream deve essere eliminato ogni volta che il contenitore viene eliminato. |
| flusso | _io.BufferedRandom | r | Ottiene lo stream. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Ottiene il contenitore dello stream. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Inizializza una nuova istanza della classe [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flusso | _io.BufferedRandom | Lo stream da aprire. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Inizializza una nuova istanza della classe [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flusso | _io.BufferedRandom | Lo stream da aprire. |
| dispose_stream | bool | se impostato su <c>true</c> lo stream verrà eliminato. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Ottiene il contenitore dello stream.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | il contenitore dello stream. |


