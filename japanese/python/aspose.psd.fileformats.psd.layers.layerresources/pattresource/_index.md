---
title: "PattResource クラス"
type: docs
weight: 770
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PattResource()](#PattResource__1) | 新しい [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) クラスのインスタンスを初期化します。 |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | 新しい [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | 8 ビット用の 'Patt' タイプ ツール情報キーです。 |
| TYPE_TOOL_KEY2 [static] | int | r | 16 ビット用の 'Pat2' タイプ ツール情報キーです。 |
| TYPE_TOOL_KEY3 [static] | int | r | 32 ビット用の 'Pat3' タイプ ツール情報キーです。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | パターン データを取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースブロックデータを保存します。 |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

新しい [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) クラスのインスタンスを初期化します。

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

新しい [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | int | リソース タイプ キーです。 |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | パターン データです。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

リソースブロックデータを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

