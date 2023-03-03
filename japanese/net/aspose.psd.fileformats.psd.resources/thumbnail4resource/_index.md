---
title: Class Thumbnail4Resource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Resources.Thumbnail4Resource クラス. psd 4.0 のサムネイル リソースを表します
type: docs
weight: 3890
url: /ja/net/aspose.psd.fileformats.psd.resources/thumbnail4resource/
---
## Thumbnail4Resource class

psd 4.0 のサムネイル リソースを表します。

```csharp
public sealed class Thumbnail4Resource : ThumbnailResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Thumbnail4Resource](thumbnail4resource/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BitsPixel](../../aspose.psd.fileformats.psd.resources/thumbnailresource/bitspixel/) { get; set; } | ビット ピクセルを取得または設定します。 |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/datasize/) { get; } | リソース データ サイズをバイト単位で取得します。 |
| [Format](../../aspose.psd.fileformats.psd.resources/thumbnailresource/format/) { get; set; } | サムネイル データ形式を取得または設定します。 |
| [Height](../../aspose.psd.fileformats.psd.resources/thumbnailresource/height/) { get; set; } | サムネイルの高さをピクセル単位で取得または設定します。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | リソースの一意の識別子を取得または設定します。 |
| [JpegOptions](../../aspose.psd.fileformats.psd.resources/thumbnailresource/jpegoptions/) { get; set; } | JPEG オプションを取得または設定します。サムネイル リソースが JPEG ファイル形式のみで保存される場合に適しています。このオプションは、RAW 形式が定義されている場合は効果がありません。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/thumbnail4resource/minimalversion/) { get; } | 必要最小限の psd バージョンを取得します。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | リソース名を取得または設定します。サイズを均等にするためにパディングされた Pascal 文字列 (null 名は 2 バイトの 0 で構成されます). |
| [PlanesCount](../../aspose.psd.fileformats.psd.resources/thumbnailresource/planescount/) { get; set; } | 平面数を取得または設定します。 |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | リソース署名を取得します。常に '8BIM'. である必要があります |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | データを含むリソース ブロック サイズをバイト単位で取得します。 |
| [SizeAfterCompression](../../aspose.psd.fileformats.psd.resources/thumbnailresource/sizeaftercompression/) { get; } | 圧縮後のサイズを取得または設定します。整合性チェックに使用. |
| [ThumbnailArgb32Data](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnailargb32data/) { get; set; } | 32 ビット ARGB サムネイル データを取得または設定します。 |
| [ThumbnailData](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnaildata/) { get; set; } | サムネイル データを取得または設定します。 |
| [TotalSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/totalsize/) { get; } | 総データサイズを取得します。 |
| [Width](../../aspose.psd.fileformats.psd.resources/thumbnailresource/width/) { get; set; } | サムネイルの幅をピクセル単位で取得または設定します。 |
| [WidthBytes](../../aspose.psd.fileformats.psd.resources/thumbnailresource/widthbytes/) { get; } | 行幅をバイト単位で取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 指定したストリームにリソース ブロックを保存します。 |
| override [ValidateValues](../../aspose.psd.fileformats.psd.resources/thumbnailresource/validatevalues/)() | リソース値を検証します。 |

### 関連項目

* class [ThumbnailResource](../thumbnailresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 組み立て [Aspose.PSD](../../)


