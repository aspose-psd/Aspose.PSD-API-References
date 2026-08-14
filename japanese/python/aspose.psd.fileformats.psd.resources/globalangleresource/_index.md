---
title: "GlobalAngleResource クラス"
type: docs
weight: 100
url: /ja/python-net/aspose.psd.fileformats.psd.resources/globalangleresource/
---

**Summary:** Global angle resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GlobalAngleResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GlobalAngleResource()](#GlobalAngleResource__1) | GlobalAngleResource クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady のリソース署名です。 |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 通常の Photoshop リソース署名です。 |
| data_size | int | r | リソースデータサイズ（バイト）を取得します。 |
| global_angle | int | r/w | 全体の角度を取得または設定します。 |
| id | short | r/w | リソースの一意の識別子を取得または設定します。 |
| minimal_version | int | r | 必要最低限の PSD バージョンを取得します。 |
| name | string | r/w | リソース名を取得または設定します。Pascal 文字列で、サイズを偶数にするためにパディングされます（null 名は 0 のバイトが2つで構成されます）。 |
| signature | int | r | リソース署名を取得します。常に '8BIM' である必要があります。 |
| サイズ | int | r | データを含むリソースブロックのサイズ（バイト）を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream)](#save_stream_1) | リソースブロックを指定されたストリームに保存します。 |
| validate_values() | リソースの値を検証します。 |


### Constructor: GlobalAngleResource() {#GlobalAngleResource__1}


```
 GlobalAngleResource() 
```

GlobalAngleResource クラスの新しいインスタンスを初期化します。

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

リソースブロックを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | リソースブロックを保存するストリームです。 |

