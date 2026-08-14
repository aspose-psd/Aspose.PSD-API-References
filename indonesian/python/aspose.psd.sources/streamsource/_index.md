---
title: "Kelas StreamSource"
type: docs
weight: 40
url: /id/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | Menginisialisasi sebuah instance baru dari kelas [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Menginisialisasi sebuah instance baru dari kelas [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Mendapatkan nilai yang menunjukkan apakah aliran harus dibuang setiap kali kontainer dibuang. |
| aliran | _io.BufferedRandom | r | Mendapatkan aliran. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Mendapatkan kontainer aliran. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Menginisialisasi sebuah instance baru dari kelas [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran yang akan dibuka. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Menginisialisasi sebuah instance baru dari kelas [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran yang akan dibuka. |
| dispose_stream | bool | jika diatur ke <c>true</c> aliran akan dibuang. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Mendapatkan kontainer aliran.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | kontainer aliran. |


