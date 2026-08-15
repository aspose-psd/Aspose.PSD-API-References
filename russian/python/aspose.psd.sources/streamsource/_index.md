---
title: "Класс StreamSource"
type: docs
weight: 40
url: /ru/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | Инициализирует новый экземпляр класса [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Инициализирует новый экземпляр класса [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Получает значение, указывающее, следует ли освобождать поток при освобождении контейнера. |
| поток | _io.BufferedRandom | r | Получает поток. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Получает контейнер потока. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Инициализирует новый экземпляр класса [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для открытия. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Инициализирует новый экземпляр класса [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для открытия. |
| dispose_stream | bool | Если установлено в <c>true</c>, поток будет освобожден. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Получает контейнер потока.

**Returns**

| Тип | Описание |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | контейнер потока. |


