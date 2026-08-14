---
title: "StreamSource クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | 新しい [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) クラスのインスタンスを初期化します。 |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | 新しい [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | コンテナが破棄されるたびにストリームを破棄すべきかどうかを示す値を取得します。 |
| ストリーム | _io.BufferedRandom | r | ストリームを取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | ストリーム コンテナを取得します。 |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

新しい [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 開くストリームです。 |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

新しい [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 開くストリームです。 |
| dispose_stream | bool | <c>true</c> に設定すると、ストリームが破棄されます。 |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

ストリーム コンテナを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリーム コンテナです。 |


