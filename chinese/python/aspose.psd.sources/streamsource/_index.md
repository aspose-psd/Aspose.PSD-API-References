---
title: "StreamSource 类"
type: docs
weight: 40
url: /zh/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | 初始化 [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) 类的新实例。 |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | 初始化 [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | 获取一个值，指示在容器被释放时是否应释放流。 |
| 流 | _io.BufferedRandom | r | 获取流。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | 获取流容器。 |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

初始化 [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要打开的流。 |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

初始化 [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要打开的流。 |
| dispose_stream | bool | 如果设置为 <c>true</c>，流将被释放。 |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

获取流容器。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |


