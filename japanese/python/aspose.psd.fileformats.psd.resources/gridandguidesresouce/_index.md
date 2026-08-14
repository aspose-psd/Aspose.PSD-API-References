---
title: "GridAndGuidesResouce クラス"
type: docs
weight: 110
url: /ja/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | GridAndGuidesResouce クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady のリソース署名です。 |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 通常の Photoshop リソース署名です。 |
| data_size | int | r | リソースデータサイズ（バイト）を取得します。 |
| grid_cycle_x | int | r/w | 水平グリッドサイクルを取得または設定します。デフォルトは 576 です。 |
| grid_cycle_y | int | r/w | 垂直グリッドサイクルを取得または設定します。デフォルトは 576 です。 |
| guide_count | int | r | ガイドリソースブロックの数を取得します。 |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | ガイドを取得または設定します。 |
| header_version | int | r/w | ヘッダー バージョンを取得または設定します。この値は常に 1 である必要があります。 |
| id | short | r/w | リソースの一意の識別子を取得または設定します。 |
| minimal_version | int | r | 最小限の必要な psd バージョンを取得します。 |
| name | string | r/w | リソース名を取得または設定します。Pascal 文字列で、サイズを偶数にするためにパディングされます（null 名は 0 のバイトが2つで構成されます）。 |
| signature | int | r | リソース署名を取得します。常に '8BIM' である必要があります。 |
| サイズ | int | r | データを含むリソースブロックのサイズ（バイト）を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream)](#save_stream_1) | リソースブロックを指定されたストリームに保存します。 |
| validate_values() | リソースの値を検証します。 |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

GridAndGuidesResouce クラスの新しいインスタンスを初期化します。

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

リソースブロックを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | リソースブロックを保存するストリームです。 |

