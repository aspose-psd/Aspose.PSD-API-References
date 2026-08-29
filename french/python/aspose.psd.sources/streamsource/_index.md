---
title: "Classe StreamSource"
type: docs
weight: 40
url: /fr/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | Initialise une nouvelle instance de la classe [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Initialise une nouvelle instance de la classe [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Obtient une valeur indiquant si le flux doit être libéré chaque fois que le conteneur est libéré. |
| flux | _io.BufferedRandom | r | Obtient le flux. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Obtient le conteneur du flux. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Initialise une nouvelle instance de la classe [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux à ouvrir. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Initialise une nouvelle instance de la classe [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux à ouvrir. |
| dispose_stream | bool | si défini sur <c>true</c> le flux sera libéré. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Obtient le conteneur du flux.

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | le conteneur du flux. |


