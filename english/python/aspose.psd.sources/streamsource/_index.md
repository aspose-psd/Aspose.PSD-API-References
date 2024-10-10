---
title: StreamSource Class
type: docs
weight: 40
url: /python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | Initializes a new instance of the [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) class. |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Initializes a new instance of the [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Gets a value indicating whether stream should be disposed whenever container gets disposed. |
| stream | _io.BufferedRandom | r | Gets the stream. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Gets the stream container. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Initializes a new instance of the [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to open. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Initializes a new instance of the [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to open. |
| dispose_stream | bool | if set to <c>true</c> the stream will be disposed. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Gets the stream container.

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | the stream container. |


