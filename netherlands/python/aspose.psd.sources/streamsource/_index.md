---
title: "StreamSource Klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | Initialiseert een nieuw exemplaar van de [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) klasse. |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Initialiseert een nieuw exemplaar van de [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Haalt een waarde op die aangeeft of de stream moet worden verwijderd telkens wanneer de container wordt verwijderd. |
| stroom | _io.BufferedRandom | r | Haalt de stream op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Haalt de streamcontainer op. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Initialiseert een nieuw exemplaar van de [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om te openen. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Initialiseert een nieuw exemplaar van de [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om te openen. |
| dispose_stream | bool | indien ingesteld op <c>true</c> wordt de stream verwijderd. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Haalt de streamcontainer op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | de streamcontainer. |


