---
title: "LayerSelectionIdsResource クラス"
type: docs
weight: 170
url: /ja/python-net/aspose.psd.fileformats.psd.resources/layerselectionidsresource/
---

**Summary:** Layer selection ids resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.LayerSelectionIdsResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LayerSelectionIdsResource()](#LayerSelectionIdsResource__1) | LayerSelectionIdsResource クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady のリソース署名です。 |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 通常の Photoshop リソース署名です。 |
| count | short | r/w | カウントを取得または設定します。 |
| data_size | int | r | リソースデータサイズ（バイト）を取得します。 |
| id | short | r/w | リソースの一意の識別子を取得または設定します。 |
| layer_ids | int | r/w | レイヤー ID を取得または設定します。 |
| minimal_version | int | r | 必要最低限の PSD バージョンを取得します。 |
| name | string | r/w | リソース名を取得または設定します。Pascal 文字列で、サイズを偶数にするためにパディングされます（null 名は 0 のバイトが2つで構成されます）。 |
| signature | int | r | リソース署名を取得します。常に '8BIM' である必要があります。 |
| サイズ | int | r | データを含むリソースブロックのサイズ（バイト）を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream)](#save_stream_1) | リソースブロックを指定されたストリームに保存します。 |
| validate_values() | リソースの値を検証します。 |


### Constructor: LayerSelectionIdsResource() {#LayerSelectionIdsResource__1}


```
 LayerSelectionIdsResource() 
```

LayerSelectionIdsResource クラスの新しいインスタンスを初期化します

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

リソースブロックを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | リソースブロックを保存するストリームです。 |

