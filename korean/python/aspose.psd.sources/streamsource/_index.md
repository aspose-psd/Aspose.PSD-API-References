---
title: "StreamSource 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | 새로운 [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) 클래스 인스턴스를 초기화합니다. |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | 새로운 [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | 컨테이너가 폐기될 때 스트림을 폐기해야 하는지 여부를 나타내는 값을 가져옵니다. |
| 스트림 | _io.BufferedRandom | r | 스트림을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | 스트림 컨테이너를 가져옵니다. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

새로운 [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 열 스트림입니다. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

새로운 [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 열 스트림입니다. |
| dispose_stream | bool | 만약 <c>true</c> 로 설정하면 스트림이 폐기됩니다. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

스트림 컨테이너를 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |


