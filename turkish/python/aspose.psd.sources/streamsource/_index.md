---
title: "StreamSource Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | Yeni bir [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) sınıfı örneği oluşturur. |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Yeni bir [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) sınıfı örneği oluşturur. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Konteyner atıldığında akışın da atılıp atılmayacağını gösteren bir değeri alır. |
| akış | _io.BufferedRandom | r | Akışı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Akış konteynerini alır. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Yeni bir [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) sınıfı örneği oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Açılacak akış. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Yeni bir [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) sınıfı örneği oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Açılacak akış. |
| dispose_stream | bool | eğer <c>true</c> olarak ayarlanırsa akış atılacaktır. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Akış konteynerini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | akış konteyneri. |


