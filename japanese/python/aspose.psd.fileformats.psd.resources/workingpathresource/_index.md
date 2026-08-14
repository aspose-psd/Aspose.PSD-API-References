---
title: "WorkingPathResource クラス"
type: docs
weight: 320
url: /ja/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Summary:** Working path resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.WorkingPathResource

**Inheritance:** IVectorPathData, ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [WorkingPathResource(data_bytes)](#WorkingPathResource_data_bytes_1) | 新しい [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady のリソース署名です。 |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 通常の Photoshop リソース署名です。 |
| data_size | int | r | リソースデータサイズ（バイト）を取得します。 |
| id | short | r/w | リソースの一意の識別子を取得または設定します。 |
| is_disabled | bool | r/w | このインスタンスが無効かどうかを示す値を取得または設定します。 |
| is_inverted | bool | r/w | このインスタンスが反転しているかどうかを示す値を取得または設定します。 |
| is_not_linked | bool | r/w | このインスタンスがリンクされていないかどうかを示す値を取得または設定します。 |
| minimal_version | int | r | 必要最低限の PSD バージョンを取得します。 |
| name | string | r/w | リソース名を取得または設定します。Pascal 文字列で、サイズを偶数にするためにパディングされます（null 名は 0 のバイトが2つで構成されます）。 |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | パス レコードを取得または設定します。 |
| signature | int | r | リソース署名を取得します。常に '8BIM' である必要があります。 |
| サイズ | int | r | データを含むリソースブロックのサイズ（バイト）を取得します。 |
| version | int | r/w | バージョンを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream)](#save_stream_1) | リソースブロックを指定されたストリームに保存します。 |
| validate_values() | リソースの値を検証します。 |


### Constructor: WorkingPathResource(data_bytes) {#WorkingPathResource_data_bytes_1}


```
 WorkingPathResource(data_bytes) 
```

新しい [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data_bytes | byte | ベクターパスのデータです。 |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

リソースブロックを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | リソースブロックを保存するストリームです。 |

