---
title: "ClblResource クラス"
type: docs
weight: 160
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | 新しい [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) クラスのインスタンスを初期化します。 |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | 新しい [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) クラスのインスタンスを初期化します。 |
| [ClblResource(data)](#ClblResource_data_3) | 新しい [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) クラスのインスタンスを初期化します。<br/>            カスタムまたは不明な値で |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| blend_clipped_elements | bool | r/w | ブレンドクリップ要素かどうかを示す値を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 指定されたストリームコンテナを保存します。 |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

新しい [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) クラスのインスタンスを初期化します。

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

新しい [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| blend_clipped_elements | bool | true に設定すると、[ブレンドクリップ要素]が有効になります。 |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

新しい [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) クラスのインスタンスを初期化します。<br/>            カスタムまたは不明な値で

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | リソース データ。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

指定されたストリームコンテナを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

