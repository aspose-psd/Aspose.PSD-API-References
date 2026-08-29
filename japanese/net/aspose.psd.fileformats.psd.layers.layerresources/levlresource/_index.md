---
title: "クラス LevlResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource クラス。クラス LevlResource。露光調整レイヤーのリソースです。"
type: docs
weight: 2950
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

クラス LevlResource。露光調整レイヤーのリソース。

```csharp
public class LevlResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | `LevlResource` クラスの新しいインスタンスを初期化します。 |
| [LevlResource](levlresource/#constructor_1)(byte[]) | `LevlResource` クラスの新しいインスタンスを初期化します。GrayScale、Duotone、RGB、CMYK、Lab カラーモードでサポートされます。2 バイト - バージョン (=2) 29 * 10 バイト - 5 つのショート整数で構成されるレベルレコードのセット 4 バイト - Lvls ヘッダー（インデックス 292 から開始） 2 バイト - バージョン (=3) 2 バイト - 総レベルレコード数 10 * (総数 - 29) Lvls リソースのゼロ終端は 4 バイトに合わせて折りたたむ必要があります。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | バージョンを取得します。デフォルトは 2 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | チャンネルを取得します。 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | タイプツール情報キーです。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


