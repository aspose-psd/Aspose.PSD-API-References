---
title: "MixrResource クラス"
type: docs
weight: 680
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | 新しい [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) クラスのインスタンスを初期化します。<br/>            PSD フォーマットの仕様には以下の記述が含まれます:<br/>            2 バージョン (= 1)<br/>            2 モノクローム<br/>            20 RGB または CMYK カラーに加えてミキサー設定用の定数。色は 4 * 2 バイト、定数は 2 バイトです。 |
| [MixrResource(data)](#MixrResource_data_2) | 新しい [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) クラスのインスタンスを初期化します。<br/>            PSD フォーマットの仕様には以下の記述が含まれます:<br/>            2 バージョン (= 1)<br/>            2 モノクローム<br/>            20 RGB または CMYK カラーに加えてミキサー設定用の定数。色は 4 * 2 バイト、定数は 2 バイトです。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| monochrome | bool | r/w | この [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) がモノクロームかどうかを示す値を取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
| version | short | r/w | バージョンを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | チャネル情報の生データを取得します |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | リソースを指定されたストリームコンテナに保存します。 |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | チャネル情報を設定します。 |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

新しい [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) クラスのインスタンスを初期化します。<br/>            PSD フォーマットの仕様には以下の記述が含まれます:<br/>            2 バージョン (= 1)<br/>            2 モノクローム<br/>            20 RGB または CMYK カラーに加えてミキサー設定用の定数。色は 4 * 2 バイト、定数は 2 バイトです。

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

新しい [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) クラスのインスタンスを初期化します。<br/>            PSD フォーマットの仕様には以下の記述が含まれます:<br/>            2 バージョン (= 1)<br/>            2 モノクローム<br/>            20 RGB または CMYK カラーに加えてミキサー設定用の定数。色は 4 * 2 バイト、定数は 2 バイトです。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | リソースのデータです。 |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

チャネル情報の生データを取得します

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| byte | チャネル情報の生バイト配列です。 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

リソースを指定されたストリームコンテナに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

チャネル情報を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |
| 値 | byte | 値です。 |

