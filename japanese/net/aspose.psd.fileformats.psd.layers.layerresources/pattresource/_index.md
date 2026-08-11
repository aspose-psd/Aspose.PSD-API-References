---
title: "クラス PattResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PattResource クラス。クラス PattResource。パターンデータを持つリソースです。"
type: docs
weight: 3220
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---
{{< psd/tize >}}
## PattResource class

PattResource クラス。パターンデータを含むリソース

```csharp
public class PattResource : LayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PattResource](pattresource/#constructor)() | `PattResource` クラスの新しいインスタンスを初期化します。 |
| [PattResource](pattresource/#constructor_1)(int, PattResourceData[]) | `PattResource` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [Patterns](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/patterns/) { get; set; } | パターン データを取得または設定します; |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/save/)(StreamContainer, int) | リソースブロックデータを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/typetoolkey/) | 8ビット用の 'Patt' タイプ ツール情報キーです。 |
| const [TypeToolKey2](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/typetoolkey2/) | 16ビット用の 'Pat2' タイプ ツール情報キーです。 |
| const [TypeToolKey3](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/typetoolkey3/) | 32ビット用の 'Pat3' タイプ ツール情報キーです。 |

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


