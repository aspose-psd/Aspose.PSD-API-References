---
title: Class GridAndGuidesResouce
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce クラス. グリッドとガイド リソースを表します
type: docs
weight: 3730
url: /ja/net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
## GridAndGuidesResouce class

グリッドとガイド リソースを表します。

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | リソース データ サイズをバイト単位で取得します。 |
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | 水平グリッド サイクルを取得または設定します。デフォルトは 576. です。 |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | 垂直グリッド サイクルを取得または設定します。デフォルトは 576. です。 |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | ガイド リソース ブロック数を取得します。 |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | ガイドを取得または設定します。 |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | ヘッダー バージョンを取得または設定します。この値は常に 1. にする必要があります。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | リソースの一意の識別子を取得または設定します。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | 必要最小限の psd バージョンを取得します。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | リソース名を取得または設定します。サイズを均等にするためにパディングされた Pascal 文字列 (null 名は 2 バイトの 0 で構成されます). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | リソース署名を取得します。常に '8BIM'. である必要があります |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | データを含むリソース ブロック サイズをバイト単位で取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 指定したストリームにリソース ブロックを保存します。 |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | リソース値を検証します。 |

### 関連項目

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 組み立て [Aspose.PSD](../../)


