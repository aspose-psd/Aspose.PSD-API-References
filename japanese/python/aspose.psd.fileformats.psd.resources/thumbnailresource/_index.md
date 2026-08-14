---
title: "ThumbnailResource クラス"
type: docs
weight: 250
url: /ja/python-net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Summary:** The thumbnail resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ThumbnailResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ThumbnailResource()](#ThumbnailResource__1) | ThumbnailResource クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady のリソース署名です。 |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 通常の Photoshop リソース署名です。 |
| bits_pixel | short | r/w | ビットピクセルを取得または設定します。 |
| data_size | int | r | リソースデータサイズ（バイト）を取得します。 |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | サムネイルのデータ形式を取得または設定します。 |
| 高さ | int | r/w | サムネイルの高さ（ピクセル単位）を取得または設定します。 |
| id | short | r/w | リソースの一意の識別子を取得または設定します。 |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | JPEG オプションを取得または設定します。サムネイルリソースが JPEG ファイル形式でのみ保存される場合に適しています。このオプションは RAW 形式が定義されている場合には効果がありません。 |
| minimal_version | int | r | 最小限の必要な psd バージョンを取得します。 |
| name | string | r/w | リソース名を取得または設定します。Pascal 文字列で、サイズを偶数にするためにパディングされます（null 名は 0 のバイトが2つで構成されます）。 |
| planes_count | short | r/w | 平面数を取得または設定します。 |
| signature | int | r | リソース署名を取得します。常に '8BIM' である必要があります。 |
| サイズ | int | r | データを含むリソースブロックのサイズ（バイト）を取得します。 |
| size_after_compression | int | r | 圧縮後のサイズを取得または設定します。整合性チェックに使用されます。 |
| thumbnail_argb_32_data | int | r/w | 32 ビット ARGB サムネイルデータを取得または設定します。 |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | サムネイルデータを取得または設定します。 |
| total_size | int | r | データ全体のサイズを取得します。 |
| width | int | r/w | サムネイルの幅（ピクセル単位）を取得または設定します。 |
| width_bytes | int | r | 行の幅（バイト単位）を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream)](#save_stream_1) | リソースブロックデータを保存します。 |
| validate_values() | リソースの値を検証します。 |


### Constructor: ThumbnailResource() {#ThumbnailResource__1}


```
 ThumbnailResource() 
```

ThumbnailResource クラスの新しいインスタンスを初期化します。

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

リソースブロックデータを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

