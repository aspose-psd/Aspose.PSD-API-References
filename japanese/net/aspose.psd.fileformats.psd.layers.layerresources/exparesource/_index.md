---
title: "クラス ExpaResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ExpaResource クラス。クラス ExpaResource。露光調整レイヤーのリソース"
type: docs
weight: 2710
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---
{{< psd/tize >}}
## ExpaResource class

クラス ExpaResource。露光調整レイヤーのリソース

```csharp
public class ExpaResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ExpaResource](exparesource/#constructor)() | `ExpaResource` クラスの新しいインスタンスを初期化します。 |
| [ExpaResource](exparesource/#constructor_1)(byte[]) | `ExpaResource` クラスの新しいインスタンスを初期化します。 |
| [ExpaResource](exparesource/#constructor_2)(float, float, float) | `ExpaResource` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Exposure](../../aspose.psd.fileformats.psd.layers.layerresources/exparesource/exposure/) { get; set; } | 露光を取得または設定します。 |
| [GammaCorrection](../../aspose.psd.fileformats.psd.layers.layerresources/exparesource/gammacorrection/) { get; set; } | ガンマを取得または設定します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/exparesource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/exparesource/offset/) { get; set; } | オフセットを取得または設定します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/exparesource/version/) { get; } | バージョンを取得します。デフォルトは 1 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/exparesource/typetoolkey/) | タイプツール情報キーです。 |

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


