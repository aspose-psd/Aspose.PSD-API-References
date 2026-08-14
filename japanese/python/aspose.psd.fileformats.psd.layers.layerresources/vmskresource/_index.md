---
title: "VmskResource クラス"
type: docs
weight: 1100
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/
---

**Summary:** Class VmskResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VmskResource

**Inheritance:** IVectorPathData, VectorPathDataResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [VmskResource()](#VmskResource__1) | 新しい[VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/)クラスのインスタンスを初期化します。 |
| [VmskResource(data)](#VmskResource_data_2) | 新しい[VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/)クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| is_disabled | bool | r/w | このインスタンスが無効かどうかを示す値を取得または設定します。 |
| is_inverted | bool | r/w | このインスタンスが反転しているかどうかを示す値を取得または設定します。 |
| is_not_linked | bool | r/w | このインスタンスがリンクされていないかどうかを示す値を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | パス レコードを取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
| version | int | r/w | バージョンを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: VmskResource() {#VmskResource__1}


```
 VmskResource() 
```

新しい[VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/)クラスのインスタンスを初期化します。

### Constructor: VmskResource(data) {#VmskResource_data_2}


```
 VmskResource(data) 
```

新しい[VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/)クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | リソース データ。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

リソースを指定されたストリームコンテナに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

