---
title: "CurvResource クラス"
type: docs
weight: 190
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) クラスの新しいインスタンスを初期化します。 |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| is_data_stored_discretely | bool | r/w | このインスタンスがデータを離散的に格納しているかどうかを示す値を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | アクティブなマネージャーを取得します。 |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | チャンネルデータを取得します。 |
| [get_curve_manager()](#get_curve_manager__3) | カーブマネージャーを取得します。 |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

[CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| バイト | byte | バイトです。 |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

[CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| max_channel_count | int | 最大チャネル数です。 |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

アクティブなマネージャーを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | アクティブマネージャー |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

チャンネルデータを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| channel_index | int | チャネルのインデックスです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| byte | チャンネルデータ |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

カーブマネージャーを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) または [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

リソースを指定されたストリームコンテナに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

