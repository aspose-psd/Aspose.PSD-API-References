---
title: "LevlResource クラス"
type: docs
weight: 490
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) クラスの新しいインスタンスを初期化します。 |
| [LevlResource(bytes)](#LevlResource_bytes_2) | [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) クラスの新しいインスタンスを初期化します。<br/>            GrayScale、Duotone、RGB、CMYK、Lab カラーモードでサポート<br/>            2 バイト - バージョン (=2)<br/>            29 * 10 バイト - 5 つのショート整数を含むレベルレコードのセット<br/>            4 バイト - Lvls ヘッダー (インデックス 292 から開始)<br/>            2 バイト - バージョン (=3)<br/>            2 バイト - 総レベルレコード数<br/>            10 * (総数 - 29)<br/>            Lvls リソースのゼロ終端は 4 でも折りたたむ必要があります |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
| version | short | r | バージョンを取得します。デフォルトは 2 です。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | チャネルを取得します。 |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

[LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) クラスの新しいインスタンスを初期化します。

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

[LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) クラスの新しいインスタンスを初期化します。<br/>            GrayScale、Duotone、RGB、CMYK、Lab カラーモードでサポート<br/>            2 バイト - バージョン (=2)<br/>            29 * 10 バイト - 5 つのショート整数を含むレベルレコードのセット<br/>            4 バイト - Lvls ヘッダー (インデックス 292 から開始)<br/>            2 バイト - バージョン (=3)<br/>            2 バイト - 総レベルレコード数<br/>            10 * (総数 - 29)<br/>            Lvls リソースのゼロ終端は 4 でも折りたたむ必要があります

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| バイト | byte | バイトです。 |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

チャネルを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | チャンネルのレベルデータ |


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

