---
title: "クラス MixrResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource クラス。クラス MixrResource。チャンネルミキサー調整レイヤーのリソースです。"
type: docs
weight: 3160
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

MixrResource クラス。Channel Mixer 調整レイヤーのリソース

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | `MixrResource` クラスの新しいインスタンスを初期化します。PSD フォーマット仕様には次の記述が含まれます：2 バージョン (= 1) 2 モノクローム 20 RGB または CMYK カラーにミキサー設定用の定数が加わります。4 × 2 バイトのカラーと 2 バイトの定数です。 |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | `MixrResource` クラスの新しいインスタンスを初期化します。PSD フォーマット仕様には次の記述が含まれます：2 バージョン (= 1) 2 モノクローム 20 RGB または CMYK カラーにミキサー設定用の定数が加わります。4 × 2 バイトのカラーと 2 バイトの定数です。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | `MixrResource` がモノクロームかどうかを示す値を取得または設定します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | バージョンを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | チャンネル情報の生データを取得します |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | チャンネル情報を設定します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | タイプツール情報キーです。 |

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


