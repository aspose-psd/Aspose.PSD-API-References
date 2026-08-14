---
title: "StreamSource Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | Initialisiert eine neue Instanz der Klasse [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Initialisiert eine neue Instanz der Klasse [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Liest einen Wert, der angibt, ob der Stream freigegeben werden soll, wenn der Container freigegeben wird. |
| Strom | _io.BufferedRandom | r | Liest den Stream. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Liest den Stream‑Container. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Initialisiert eine neue Instanz der Klasse [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream zum Öffnen. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Initialisiert eine neue Instanz der Klasse [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream zum Öffnen. |
| dispose_stream | bool | Wenn auf <c>true</c> gesetzt, wird der Stream freigegeben. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Liest den Stream‑Container.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container. |


